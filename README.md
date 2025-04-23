# Financial Freedom Calculator

A Python program that calculates either:
- Your projected wealth over a set number of years, or
- How many years until you reach a target wealth amount

## Functions

### `wealth_by_years(current_wealth, monthly_save, yearly_save, rate_of_return, years)`
Calculates and displays annual wealth growth over a specified period.

**Parameters:**
- `current_wealth`: Your current total savings/investments
- `monthly_save`: Amount saved each month (set to 0 if using yearly savings)
- `yearly_save`: Amount saved each year (set to 0 if using monthly savings)
- `rate_of_return`: Expected annual investment return percentage
- `years`: Number of years to project growth

**Returns:**
- Final total wealth after the specified period

### `years_till_freedom(current_wealth, monthly_save, yearly_save, rate_of_return, target_wealth)`
Calculates how many years until reaching a target wealth amount.

**Parameters:**
- `current_wealth`: Your current total savings/investments
- `monthly_save`: Amount saved each month (set to 0 if using yearly savings)
- `yearly_save`: Amount saved each year (set to 0 if using monthly savings)
- `rate_of_return`: Expected annual investment return percentage
- `target_wealth`: Desired wealth amount to achieve.

**Returns:**
- Number of years required to reach the target

## Usage
Run `main()` to start the interactive program which will prompt for:
1. Calculation type (wealth projection or years to freedom)
2. Savings frequency (monthly or yearly)
3. Financial values (current wealth, savings amount, return rate)
4. Either:
   - Number of years for projection, or
   - Target wealth amount

The program will then display the results.

## How It Works
For each year:
1. Adds annual savings (either monthly ×12 or yearly amount)
2. Applies the rate of return to the total
3. Repeats until either:
   - The specified number of years is reached, or
   - The target wealth amount is achieved
