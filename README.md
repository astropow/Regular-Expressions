import re

text = "The phone number is 123-456-7890."
pattern = r'\d{3}-\d{3}-\d{4}'
match = re.search(pattern, text)

if match:
    print("Phone number found:", match.group())
else:
    print("Phone number not found.")
