# Module 2: Volume vs. open interest

These two numbers are easy to confuse, but they answer different questions.

## 1. The key difference

## Volume

How many contracts traded today?

Every contract traded counts toward volume, whether the trade opens a new position or closes an existing one.

## Open interest (OI)

How many contracts remain open?

It counts outstanding contracts that have not yet been closed, exercised, or otherwise settled. It is generally updated after end-of-day processing, so it may lag today's volume.

### Example

Imagine a particular XYZ $100 call option expiring in December.

- Yesterday's open interest: 2,000 contracts
    
- Today's volume: 800 contracts
    

This means 800 contracts traded today, while the last reported count of outstanding contracts was 2,000.

It does not mean that 800 new positions were opened. Some or all of those trades could have closed existing positions.

## 2. How to interpret them together

Here are four common patterns. These are clues about activity, not proof of bullish or bearish intent.

|Volume|Open interest|What it may suggest|
|---|---|---|
|Low|High|A lot of positions already exist, but today's trading is relatively quiet.|
|High|High|The contract has an established pool of positions and is actively trading.|
|High|Low|Today's trading is large relative to the existing position count; potentially worth investigating.|
|High today, then OI rises next update|Increasing|Consistent with net new positions being opened, though it doesn't identify who opened them or their directional view.|

Important: Volume and OI are counts of contracts, not dollars. An option with a large contract count can still have a relatively small premium, and vice versa.

## 3. A worked example

Suppose a scanner flags a call option with these numbers:

Hypothetical XYZ $100 call

Today's volume

# 5,000

contracts traded

Previous OI

# 1,200

contracts outstanding

Volume is about 4.2 times the previous open interest. That makes today's activity notable relative to the existing position count.

The next day, updated OI is reported as 3,700.

- OI increased by 2,500 contracts.
    
- That is consistent with a net increase in outstanding positions.
    
- But it doesn't tell you whether the new positions were bullish calls, bearish call sales, hedges, or parts of multi-leg trades.
    

Notice the distinction: volume measures trading activity; the change in OI helps you assess whether outstanding positions grew or shrank overall.

## 4. Common traps

Trap 1: “Volume is greater than OI, so institutions are buying.”

No. High volume can include opening trades, closing trades, and strategies involving multiple options.

Trap 2: “Rising OI means bullish sentiment.”

No. Every option contract has both a long side and a short side. OI doesn't tell you which side has the better-informed trader.

Trap 3: “Volume is higher than OI, so today's contracts must be new.”

No. Volume counts all trading. Only the resulting change in OI helps show the net change in outstanding contracts.

Trap 4: “High volume means the stock will move sharply.”

Not necessarily. Check the option's liquidity, strike, expiry, implied volatility, and whether the activity is part of a hedge or spread.

One extra detail: an option trade always has a buyer and a seller. When people say “call buying,” they usually mean a buyer is initiating the trade or paying the ask. That still doesn't prove the buyer is making a directional bet.