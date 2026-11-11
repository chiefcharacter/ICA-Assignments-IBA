# My first Attempt (NO AI YET)

**Dataset:** teaching_prices_messy.csv

**Dataset size:** 97 rows and 6 columns.

### Problem I Founded

**Missing Value**
- Code used: `raw.isna().sum()`
- Observation: there seem to be a value missing (price was 1 instead of 0 which means a price is missing)
- My decision: I cannt guess the price myself, but I can see if its because of string etc
-

**Duplicate**
- Code used: `raw.duplicated().sum()`
- Observation: there is 1 duplicates (8 and 96 are duplicates)
- My decision: I will remove it
- 
**Item Name**
- Code used: `raw["item"].value_counts()`
- Observation: one item is named oil b instead of Oil B!
- My decision: I will change name but I dont know the code so i will later rely on AI help

**Comma Issue (Registering str isntead of Numeric)**
- Code used: `pd.to_numeric(raw["price"], errors="coerce")`
- Observation: Price wasnt numeric (was string) due to a comma being registerd as str
- My decision: I will change it to numeric value

### My Cleaning Plan

I plan to:
1. Remove any duplciate values or numbers
2. Change any strings that must be numeric to numbers
3. Get rid of missing value (since I cannot guess) or see if it's there 