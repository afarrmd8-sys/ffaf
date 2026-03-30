# ffafimport random

# List of fun, positive "rules" for a friend
rules = [
    "Rule #1: Always share your snacks with friends! 🍕",
    "Rule #2: High-five strangers who look sad. ✋",
    "Rule #3: Dance like nobody's watching (even if they are). 💃",
    "Rule #4: Say 'yes' to spontaneous adventures. 🚀",
    "Rule #5: Compliment at least 3 people daily. 😊",
    "Rule #6: Never skip dessert. 🍨",
    "Rule #7: Hug your friends for no reason. 🤗",
    "Rule #8: Laugh at your own jokes. 😂",
    "Rule #9: Chase your dreams, not your ex. 🌟",
    "Rule #10: Be awesome today! 🚀"
]

# Generate and print a random rule
random_rule = random.choice(rules)
print("Here's a good rule for your friend:")
print(random_rule)

# Optional: Save to a file to share
with open("good_rule_for_friend.txt", "w") as f:
    f.write(random_rule)
print("\nSaved to 'good_rule_for_friend.txt' – share it!")
