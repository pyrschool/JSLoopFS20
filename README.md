# Sample loop assignments
## debt.html
The page gives the user a loan; it prompts the user for the amount.

Then the page asks for the payback; it prompts the user to give back the money.

The user gives a part of the loan. The page informs on the new balance and keeps asking for the payback.

Here is a sample execution

1. The page asks the user for the loan amount. It prompts "How much money do you want?" and the user writes, say, 100
1. The page prompts for a payback "Give me my money!" and the user writes 20
1. the page alerts "Ok, now you owe me 80".
1. The user still owes money so we repeat from step 2
1. When The loan is payed back then the page should not prompt for payback anymore and thank the user.

## myname.html
The page prompts the user to say the author's name (that's your name :) ). As long as the user writes something else, the page prompts again. When he writes your name, say "congrats".

As an addition, keep rtack on haow many times the user tried. After he writes your name you say "congrats, it took you 4 times".

## verify.html
The page is booking medical appointments. It is asking for the user's full name, year of birth, social security number (AMKA in greek) and doctor specialty. The page should verify the data entry. Valid entries are:

1. year od birth - the user should be an adult (older than 18 years) in order to book an appointment
1. AMKA should be a string with 11 characters. In order to determine the length of the string you may refer to https://www.w3schools.com/jsref/jsref_length_string.asp
1. The doctor specialty should be one of these strings: PATH, CARD, ORTH or OPHTH (for pathology, cardiology, orthopedics, ophthalmology)
1. Full name - accept all entries that are not empty. You should research for this one.


Try to give descriptive prompts, that will facilitate the user

