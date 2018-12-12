Cross-Site Scripting Example.
Using the input field, users were able to post html code that would alter the website.

To fix this, we had to alter main.py and replace the characters '<' and '>' with '&lt' and '&gt' respectively.
