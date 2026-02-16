THEORY

** Positive, Negative, or Zero Check Theory: **

A number can be:

Positive → Greater than 0

Negative → Less than 0

Zero → Equal to 0

Conditional statements compare the number with zero and decide its category.

Algorithm:

Start

Input a number

If number > 0 → Print "Positive"

Else if number < 0 → Print "Negative"

Else → Print "Zero"

Stop

2️⃣ Even or Odd Number Theory:

A number is:

Even if divisible by 2

Odd if not divisible by 2

The modulus operator (%) is used to check the remainder.

Algorithm:

Start

Input a number

If number % 2 equals 0 → Print "Even"

Else → Print "Odd"

Stop

3️⃣ Greatest of Three Numbers Theory:

To determine the largest number among three values, comparisons are made using logical AND (and) operator.

Algorithm:

Start

Input three numbers

If first number is greater than both others → Print first number is greatest

Else if second number is greater than both others → Print second number is greatest

Else → Print third number is greatest

Stop

4️⃣ Student Grade Calculation Theory:

The average score of three subjects is calculated. Based on the average, grades are assigned:

75 and above → Grade A

60–74 → Grade B

40–59 → Grade C

Below 40 → Grade F

Algorithm:

Start

Input three subject names and scores

Calculate average

If average ≥ 75 → Assign Grade A

Else if average ≥ 60 → Assign Grade B

Else if average ≥ 40 → Assign Grade C

Else → Assign Grade F

Display average and grade

Stop

5️⃣ Leap Year Check Theory:

A year is a leap year if:

It is divisible by 400 OR

It is divisible by 4 but not divisible by 100

Logical operators are used for this condition.

Algorithm:

Start

Input year

If (year divisible by 400) OR (year divisible by 4 AND not divisible by 100) → Print "Leap Year"

Else → Print "Not a Leap Year"

Stop

6️⃣ Vowel or Consonant Check Theory:

A character is a vowel if it belongs to: a, e, i, o, u (both uppercase and lowercase). Otherwise, it is a consonant.

Algorithm:

Start

Input a character

If character is in vowel list → Print "Vowel"

Else → Print "Consonant"

Stop

7️⃣ Salary Calculation (HRA & DA) Theory:

Gross Salary = Basic Salary + HRA + DA

HRA (House Rent Allowance) and DA (Dearness Allowance) depend on salary range:

Basic ≤ 10000 → HRA = 20%, DA = 80%

Basic ≤ 20000 → HRA = 25%, DA = 90%

Above 20000 → HRA = 30%, DA = 95%

Algorithm:

Start

Input basic salary

If salary ≤ 10000 → Calculate HRA and DA accordingly

Else if salary ≤ 20000 → Calculate accordingly

Else → Calculate accordingly

Compute Gross Salary

Display HRA, DA, and Gross Salary

Stop

8️⃣ Income Tax Calculation Theory:

Tax rate depends on annual income:

Income ≤ 2,50,000 → No tax

Income ≤ 5,00,000 → 5%

Income ≤ 10,00,000 → 20%

Above 10,00,000 → 30%

Algorithm:

Start

Input annual income

If income ≤ 250000 → Tax = 0

Else if income ≤ 500000 → Tax = 5%

Else if income ≤ 1000000 → Tax = 20%

Else → Tax = 30%

Display tax amount

Stop

9️⃣ Date Validation and Increment Theory:

The number of days in a month varies:

31 days → Jan, Mar, May, Jul, Aug, Oct, Dec

30 days → Apr, Jun, Sep, Nov

February → 28 days (29 in leap year)

The program checks whether a date is valid and calculates the next day.

Algorithm:

Start

Input date in dd/mm/yyyy format

Separate day, month, year

Determine maximum days in the given month

If month invalid → Print invalid date

Else if day invalid → Print invalid date

Else if day equals maximum and month not December → Set day = 1 and increment month

Else if day = 31 and month = December → Set day = 1, month = 1, increment year

Else → Increment day

Display incremented date

Stop
