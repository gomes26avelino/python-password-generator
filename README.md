# python-password-generator
A simple and secure random password generator built with Python.

🔐 Python Password Generator
Two simple Python scripts that generate random passwords. One is quick and automatic, the other lets you customize the length.
What it does
I made these while learning Python basics like randomization, string operations, and user input. They're straightforward tools that actually come in handy when you need a strong password quickly.
What's included
python-password-generator.py
The simple version. Run it and get a 16-character password instantly. Uses uppercase, lowercase, numbers, and symbols. No questions asked, just generates and prints.
random_password_gen.py
The customizable version. You pick the length, and it builds a password with a balanced mix of characters:

50% letters (random upper/lower case)
30% numbers
20% special symbols

Then it shuffles everything so the pattern isn't predictable.
Running them
Clone the repo and run either script:
bashgit clone https://github.com/gomes26avelino/python-password-generator.git
cd python-password-generator
python python-password-generator.py
Or for the custom version:
bashpython random_password_gen.py
No dependencies needed. Just Python 3.
What I learned

Using Python's random and string modules
Building strings programmatically
Getting and validating user input
Shuffling lists to avoid patterns
Basic security concepts for password strength

Notes

The automatic version always makes 16-character passwords
The custom version lets you choose any length, but shorter passwords are obviously weaker
Both use Python's pseudorandom generator, which is fine for personal use but not cryptographically secure for high-security applications
The character mix in the custom version helps meet most password requirements (uppercase, lowercase, numbers, symbols)

Simple tools, but useful. Feel free to modify them or use them as a starting point for learning Python.
