##This code is a financial calculator that helps you understand how your savings grow over time, either showing your wealth after a certain number of years or calculating how long it will take to reach a financial goal.
#There are 3 main parts:

    #wealth_by_years()

        Shows how your money grows each year for a set period

        Takes your current savings, monthly/yearly savings amount, and investment return rate

        Calculates and prints your total wealth year by year

    #years_till_freedom()

        Calculates how many years until you reach a target savings amount

        Works similarly but keeps counting years until you hit your goal

        Tells you when you'll reach "financial freedom" (your target)

    #main()

        The user interface that asks what you want to calculate

        Asks whether you save monthly or yearly

        Gathers all the needed numbers (current savings, savings amount, return rate, etc.)

        Then runs either wealth_by_years or years_till_freedom based on your choice

#How it works:

    Your money grows through both your regular savings and investment returns

    Each year, it adds your savings (monthly*12 or yearly amount) to your total

    Then it applies the investment return (like interest) to the whole amount

    This repeats year after year until either the time period ends or you reach your goal
