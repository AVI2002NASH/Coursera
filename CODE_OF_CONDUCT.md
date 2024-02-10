def calculate_simple_interest(principal, time, rate):
    simple_interest = principal * time * rate
    return simple_interest

# Input values
p = float(input("Enter the principal amount: "))
t = float(input("Enter the time period in years: "))
r = float(input("Enter the annual rate of interest: "))

# Calculate simple interest
simple_interest = calculate_simple_interest(p, t, r)

# Output
print("Simple Interest = ", simple_interest)
