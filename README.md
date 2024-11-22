This is just a readme,
# Define a fixed exchange rate (e.g., 1 USD = 0.85 EUR)
exchange_rate = 0.85

def convert_currency(amount_usd, rate):
    return amount_usd * rate

# Prompt the user to enter an amount in USD
amount_usd = float(input("Enter the amount in USD: "))

# Convert the amount to EUR
amount_eur = convert_currency(amount_usd, exchange_rate)

# Display the converted amount
print(f"The amount in EUR is: {amount_eur:.2f}")
