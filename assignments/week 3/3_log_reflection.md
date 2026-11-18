# LOG REFLECTION

# ASK

Using chatgpt, i asked it to make a prompt from my stat values, and then I used the prompt to get AI suggestions which I marked based on the green, amber and red marking rule.

# AI PROMPT USED: 

I calculated the mean, median and percentage change for four items in City 1 and City 2

Oil B
Mean 316.18
Median 324.0
City 1 15.44%
City 2 15.13%.

Pulse C
Mean 205.9
Median 206.0
City 1 3.75%,
City 2 2.4%

Staple A
Mean 160.8
Median 112.5
City 1 13.37% 
City 2 12.62%

Sweetener D 
Mean 576.8 
Median 167.75 
City 1 19.8% 
City 2 19.03%

Staple A with flagged value mean is 160.8 and Median 112.5

Staple A without flagged value meean 111.3, Median 112.5

Interpret my results and also explain my stats to me, i.e mean, median and their differences.
Also make a claim that I will identify whether its provable by data or not.

# AI RESPONSE (MARKED AS GREEN, AMBER AND RED)

GREEN (I can verify with code)
- Oil B and Pulse C have similar means and medians.
- Staple A's high observation increases its mean.
- Sweetener D has a large mean–median difference.
- Removing Staple A's flagged value lowers the mean but leaves the median unchanged.
- The percentage changes are similar across both cities.

AMBER (Explanitn)

- Oil B: Lower values may be pulling the mean down, but the mean–median difference alone doesn't prove this.
- Pulse C: Similar mean and median suggest little effect from extreme values, but don't prove there are none.
- Staple A and Sweetener D: The differences suggest unusual observations. Check the actual data to identify them.

RED (Claim or data not shwon)
- Inflation caused Sweetener D's price to increase.

# Verification and Evaluation
I checked AIs stats against mine and are same. The explanation porvided were put in the AMBER or explanation section, while the data or stast weree put into GREEN or verifiable with recomputing section.

The "inflation caused sweetner D's price to increas" is a claim, and I cannot verifyt it. 

---------------------------------------------------------------------------------------------------------

# Cofused Classmate:

# Classmate:

"Wait, I don't get it. If the mean uses every single value, shouldn't it always be more accurate than the median? Why would we use the median instead?"

# Me:

Mean uses every single value, but it isn't more accurate because if there is a very high or very low value, it can cahnge the mean extrtemely. The median however is much less sensitive to extreme values.

# Classmate:

"Ohhh, so basically the mean gets affected more by extreme values, while the median doesn't change as much.

But then why don't we ALWAYS use the median? What's the point of calculating the mean if it's so easily affected by outliers?"

# Me:

We do not always use the median, sometimes we also use mean. In many data questions we need to take in acocunt the extreme values as well to get accurate data. Also mean takes all the values into account while median doesn't.

# Classmate:

"Okay, I think I'm getting it now. So the mean is useful when we want every observation to contribute to the result, while the median is useful when extreme values might distort the average.

But what about our Staple A data? We had that unusually high value of 1,250. Shouldn't we just delete it since it's making our mean higher?"

# Me;

We cannot just delete a high value, beacuse values can fluctuate. Also median was better in this situation.

# Classmate:

"Oh, so we shouldn't delete it just because it's unusually high. We should first check whether it's a genuine observation or a mistake.

And since the median stayed at 112.5 even after removing the 1,250, it gives us a more stable picture of the typical price in this case. Right?"

# Me:

Yess,

# Reflect:

Looking back at my own interpretation before AI, I can see that I had some very basic misunderstadings like saying that mean is more accurate than median, but it turns out that no one is more accurate than the other, they both are for different purposes.

Also I stated that same or close mean and median mean that there are no outlier, but i was wrong and outliers can exist even with close mean and median vlaues.