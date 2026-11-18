# PLP Python Week 6 Assignment - Safe Tools

## Files
- **safe_tools.py** - Contains safe_divide, safe_number, and get_field functions that use try/except to prevent crashes.
- **README.md** - Describes this assignment and explains error handling.

## Why can the if check not catch abc on its own?
An if check can only test a condition you already thought of, but it cannot stop int("abc") from raising a ValueError when it runs. Only try/except can catch the error at the exact moment the conversion fails and keep the program running.
