MINDZI TEST CHECKOUT
====================

Purpose
-------
This folder is only for testing the hardened Apps Script and Razorpay Test Mode.
It does not use the production backend and it does not send GA4 or Meta Pixel events.

TEST backend
------------
https://script.google.com/macros/s/AKfycbwJ7TdsiMv4OGVEy9eVbwoL73dnff1nAMo5Rq3LkYZZ9p_TjJ0J__oszDoFy8pf4-t1/exec

Suggested temporary GitHub Pages path
-------------------------------------
Upload the entire folder named `test-checkout` to the ROOT of the existing GitHub repository.
Then open:
https://www.mindziai.com/test-checkout/

Do not replace the live root index.html with this test page.
Delete the test-checkout folder after all tests are complete.

Expected full test
------------------
1. Enter your own email and test buyer details.
2. Select one copy (₹199).
3. Complete Razorpay Test Checkout using Razorpay's test credentials.
4. Confirm a TEST invoice and email are generated.
5. Confirm the Invoice_Counter sheet does not advance.
6. Repeat verification/reload checks to confirm no duplicate invoice/email.
