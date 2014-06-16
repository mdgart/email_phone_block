email/phone block
=================

A simple python function to substitute emails and phone number with dummies.

Unittest included.

Install
-------

pip install email_phone_block 

or

easy_install email_phone_block 


Usage
-----

    >>> from email_phone_block import block
    >>> block("So please send me an email at name@domain.com, thanks!")
    'So please send me an email at xxxx@xxxxx.xxx, thanks!'
    >>> block("So please call me at 333-333-3333, thanks!'")
    'So please call me at xxx-xxx-xxxx, thanks!'


Format Recognized
=================

Emails
------
name@domain.com  
name(at)domain.com   
name at domain.com  
 
Phone numbers
-------------
333-333-3333  
3333333333  
333 333 3333  
333 333-3333  
333333-3333  
333-3333333   