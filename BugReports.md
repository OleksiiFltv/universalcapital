## Ticket 1
**Project:** Invest

**Issue Type:** BUG

**Summary:**  Incorrect message displayed when submitting the form
**Description:**
Precondition: go to https://investe.cz/
STR:
1. In header click E-book buton
2. click button 'Stáhnout e-book'.
3. click on field 'Vaše jméno' and add Alexey
4. click on field 'Vaše příjmení' and add Filatov
5. click on field 'Mobilní telefon' and add +420 777-888-999
6. click on field 'Emailová adresa' and add oleksii65@yopmail.com
7. click on checkbox with text 'Souhlasím se zpracováním osobních údajů.'
8. click button Odeslat formulář

**Expected Result:** 
Should appears message that form sent successfully 

**Actual Result:** 
Appears message with text 'Omlouváme se. Nemáme pro vás žádnou nabídku.'[View Screenshot](screenshots/Screenshot2.png). E-book appears in email [View Screenshot](screenshots/Screenshot3.png).

**Priority:** 
critical

**labels:** 
bug, form submission, E-book, frontend

---

## Ticket 2
**Project:** Invest

**Issue Type:** BUG

**Summary:**  Modal does not open when the 'Začít s Investe' button is clicked.
**Description:**
Precondition: go to https://investe.cz/
STR:
1. Click the E-book button in the header.
2. Scroll down to the block titled 'Jak Investe funguje'.
3. Click the 'Začít s Investe' button.

   
**Expected Result:** 
Modal form opened. 

**Actual Result:** 
Modal form was not opened.[View Video 1](video/video2.mp4) (click View raw to download file)

**Priority:** 
High

**labels:** 
bug, modal form, E-book,


