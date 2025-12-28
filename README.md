# hotmail checker

a python-based hotmail / outlook account checker that verifies email and password combinations from a file.

## overview

hotmail checker is a console-based python script that tests hotmail (outlook) email credentials by sending login requests to microsoft’s authentication endpoint and analyzing the response.

the script categorizes results as:
- valid login
- two-factor authentication required
- invalid credentials

developed by sususoftware.xyz

---

## features

- bulk checking from a combo file (email:password)
- detects valid, invalid, and 2fa-protected accounts
- colored console output
- ascii interface banner
- saves valid accounts to a file

---

## requirements

- python 3.x
- required libraries:
  - requests
  - python-cfonts

install dependencies:
```bash
pip install requests python-cfonts

~~ by leoniofficials

have a questions?
website:**sususoftware.xyz**
discord:**leoniofficials**
