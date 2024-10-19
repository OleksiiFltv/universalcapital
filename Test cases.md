## Test Case 1
**Test Case Name:** Investe - E-Book page - Compare page with design

**Precondition:** Open design link (e.g. in figma)

**Steps:**  
1. go to https://investe.cz/
2. In header click E-book buton.
3. compare all elements on page with design.

**Expected Result:** 
All elements on the page match the design.

**Actual Result:** 
All elements on the page match the design [View Video 1](video/video1.mp4) (click View raw to download file)

---

## Test Case 2
**Test Case Name:** Investe - E-Book page - Check 'Stáhnout e-book' button

**Precondition:** go to https://investe.cz/

**Steps:**  
1. In header click E-book buton
2. click button 'Stáhnout e-book'.

**Expected Result:** 
Form with title 'Tady začíná vaše investiční cesta' opened.

**Actual Result:** 
Form with title 'Tady začíná vaše investiční cesta' opened successfully [View Screenshot](screenshots/Screenshot1.png).

---

## Test Case 3
**Test Case Name:** Investe - E-Book page - Fill in all fields in form - Send E-book Form to email

**Precondition:** go to https://investe.cz/

**Steps:**  
1. In header click E-book buton
2. click button 'Stáhnout e-book'.
3. click on field 'Vaše jméno' and add Alexey
4. click on field 'Vaše příjmení' and add Filatov
5. click on field 'Mobilní telefon' and add +420 777-888-999
6. click on field 'Emailová adresa' and add oleksii65@yopmail.com
7. click on checkbox with text 'Souhlasím se zpracováním osobních údajů.'
8. click button Odeslat formulář
9. Open email and check E-book

**Expected Result:** 
E-book form sent successfully. E-book appears in email

**Actual Result:** 
Appears message with text 'Omlouváme se. Nemáme pro vás žádnou nabídku.'[View Screenshot](screenshots/Screenshot2.png). E-book appears in email [View Screenshot](screenshots/Screenshot3.png).

---

## Test Case 4
**Test Case Name:** Investe - E-Book page - Send E-book Form to email without fill in all fileds

**Precondition:** go to https://investe.cz/

**Steps:**  
1. In header click E-book buton
2. click button 'Stáhnout e-book'.
3. click button Odeslat formulář


**Expected Result:** 
All empty fields are highlighted in red, and the form was not submitted.

**Actual Result:** 
All empty fields are highlighted in red, and the form was not submitted.[View Screenshot](screenshots/Screenshot4.png).

---

## Test Case 5
**Test Case Name:** Investe - E-Book page - Send E-book Form to email without fill in all fileds

**Precondition:** go to https://investe.cz/

**Steps:**  
1. In header click E-book buton
2. scroll down to block 'Jak Investe funguje'
3. click button 'Začít s Investe'


**Expected Result:** 
Modal form opened.

**Actual Result:** 
Modal form was not opened.[View Video 1](video/video2.mp4) (click View raw to download file)


