email_phone_block
=================

A simple python function to substitute emails and phone number with dummies.
Unittest included.

example
-------

text = "So please send me an email at name@domain.com, thanks!"

result: 'So please send me an email at xxxx@xxxxx.xxx, thanks!'

text = "So please call me at 333-333-3333, thanks!'"

result: 'So please call me at xxx-xxx-xxxx, thanks!'

format recognized:

Emails
------
name@domain.com
name(at)domain.com
name at domain.com

Phone numbers:

333-333-3333
3333333333
333 333 3333
333 333-3333
333333-3333
333-3333333