# daily_update.py
import datetime
import random

print("Daily GitHub activity - Day 29")

today = datetime.date.today()

# Generate a list of random temperatures and calculate some stats
temperatures = [round(random.uniform(10, 35), 2) for _ in range(7)]
highest = max(temperatures)
lowest = min(temperatures)
average = round(sum(temperatures) / len(temperatures), 2)

print(f"Today's date: {today}")
print(f"Weekly random temperatures: {temperatures}")
print(f"Highest temp: {highest}°C")
print(f"Lowest temp: {lowest}°C")
print(f"Average temp: {average}°C")
