# Trade types

There are two types of trades:
- Trend following: basically any trade where the price going up makes the buy signal stronger. For example, trading breakouts and chasing a (suspected) trend. Most breakout attempts fail, and once a trend is clearly formed it's sometimes too late to join, so trend following trades should generally be subject to more filters and need be suggested more strongly.
- Mean reversion: any trade where the price going up makes the sell signal stronger. Markets are mean reverting the majority of the time, and entry is less time sensitive, so these should generally be subject to fewer filters and need to be suggested less strongly. This adjustment should be about as strong as being in a trend in 1 to 2 larger timeframes (say monthly and weekly, for example). This is so that you end up taking mean reverting trades more often, but don't trade against a strong long + medium term trend, or need a little extra evidence to trade against a medium term trend.


# Filters

You are not allowed to enter a trade if any of these conditions aren't met.

1. it's past 11 EST and the day is looking choppy (TODO define guidelines for looking choppy?)
2. you got stopped out 4 times today
3. you didn't do your homework!
4. it's between 9:30 EST and 10:30 EST and the type of trade is mean reverting in the day timeframe. mean reverting trades are still fine as long as they're mean reverting in larger timeframes, but not in the daily timeframe.
5. news are expected very soon (next few hours, or 1 day for big ones)
6. volume should be at least decent for the kind of trade/time of day/type of day
7. abandon a trade after no more than 2 failed entries
8. if you trade a gap fade, don't enter the position earlier than 9:30 EST

You need extra evidence for the following trades:

- 1a. it's between 11 am EST and 2 pm EST and the type of trade is trend following
- 2a. it's between 12 am EST and 1 pm EST and the type of trade is trend following (even more)
- 3a. news are expected soon (next 1 day, or 2 days for big ones, but not soon enough for rule 5. to trigger) and the type of trade is trend following
- 4a. no knife catching - do not trade against a trend until you're extra sure it's over
- 5a. don't take day time frame mean reverting trade using the previous range-bound day as reference if today's range is narrower so far


# Evidence

1. call OI suggests resistance
2. put OI can act as a magnet
3. if you don't see activity indicating initiative, like Open-Drive opens, and you see a bracket forming, there have been 2 or 3 bounces, it's evidence for trading the bracket. 2 to 3 bounces should define the levels well enough.
4. if the price is accepted outside the currently accepted value, it's a sign there could be a trend starting soon. this is easier to see on the daily timeframe: the price opening or closing outside of a weekly bracket, for example, indicates balance may break soon.
5. if news indicates that the price should change a certain way, and it doesn't, it's evidence the price may take off in the opposite way. for example, if bearish news doesn't push the market down, it's bullish evidence. if neutral news doesn't push the market up, it's bearish evidence.
6. evidence produced as in 5. is made stronger or weaker based on where the price is in a bracket. for example, if we are at the top of a bracket it's more likely for neutral news to not push the market up. so the evidence is weaker. on the other hand, if neutral news fails to push the market up at the bottom of a bracket, the evidence is stronger. for the purposes of this rule, being in a downtrend is similar to being at the bottom of a bracket and viceversa
7. price gaps are evidence of imbalance in the direction of the gap. if a gap isn't filled early in the day, it's unlikely it will get filled
8. if price opens outside the previous days value area but then is accepted inside the value area, the price is likely to visit the other extreme of the previous days value area ("outside day")
9. EOD spikes produce a support if the price opens after the top of the spike. support is cancelled after double TPO prints below
10. half hour auction "turns" until noon, slight mean reverting evidence
11. london close - not directional evidence, but heightened
12. a weak bottom (top) followed by what looks like the first half of a hook
13. if there is a trend, and it reaches a resistance point, and forms a tight (ES: lte 5 points) range there for 5 to 10 minutes, this can be used for very short term scalping
14. there is some good reason to think that it's unlikely the price will go past a resistance, and there is "poor structure", it's likely that those prices will be revisited in the second half of the day

Note that some of these criteria can be applied to different timeframes, for example 3. As long as you don't stretch this - for example, by applying the rule to a 5 minute time frame or by applying it to multiple timeframes that are unreasonably close to each other, like 1 day and 2 days - each application of this criteria should indipendently add up to the total amount of evidence.

So if, for example, the current price is the bottom of a 2 day bracket and of a 1 month bracket, it counts as twice the evidence.

### Instrument specific

- 1a. Don't short ES when RTY is strong
- 1b. Since NQ is a large part of ES, if they're moving in opposite directions, ES is more likely to go nowhere (+ for mean reverting)
- 1c. Don't short NQ when XLU is going down. Utilities vs Tech is classic risk off/risk on rotation.


# Entry and exit guidelines

1. BEFORE entering a trade, think about the potential gain vs where you'd need to put your SL. If this is not satisfactory, don't enter the trade.

### Mean Reverting

- 1a. For mean reverting trades, the trade should be entered as much outside the bracket as possible. The price should go back to the highs/lows often enough. Most of the time, breakouts will fail (as long as you follow the rules) and the price will come back in the bracket. BE PATIENT! Just getting better entries should massively increase your EV given you entered trade. **Every trade not entered has an EV of 0, which is higher than your current EV**
- 2a. Trade should be exited if the price is accepted significantly outside the bracket (take "significantly" to mean it's 1/2 of the way to the SL).
- 3a. You need to use a wide SL for mean reverting trades
- 4a. PT should be somewhere you're fairly confident the price will go again as long as we spend some time inside the bracket (for an intraday trade, this could be 1/2 or 2/3 of the range)

### Trend following

- 1b. For trend following trades, you can chase if you think you're very early, otherwise, wait for a pullback. If this seems risky, don't forget you should be very selective when it comes to trend following entries.
- 2b. You should exit the trade if you see signs of a resistance/support forming against the trend, or if you know there is a strong resistance/support coming ahead.
- 3b. SL should chase the price but be far enough that it's unlike to be triggered while the trend is strong.
- 4b. you shouldn't use a single PT but gradually unwind your position at each resistance level
- 5b. when trading upwards (downwards) breakouts you should place SL just below (above) the top (bottom) that the price is breaking out of.
- 6b. when trading gap, SL should be placed at the point where the gap would be erased


# Homework

1. Mark past resistances and single prints, unfilled gaps
2. look at events coming up in the next few days
3. examine the past few days for price generated bullish or bearish evidence
4. come up with responses to hypothetical events, including no long and no short zones


# Events

1. OPEX third friday of every month
2. FOMC
3. FOMC minutes
4. 15 september tax date