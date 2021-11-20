# TestCaseFast8Group
Test case hadirr.com &amp; automationpractice.com

Test Case hadirr.com :

Sign In :
A. Positive Testing :
- Open Browser
- Navigate to hadirr.com
- Click 'Masuk' button
- Key in email (percob*****y@gmail.com)
- Key in password (12*****) 
- Click "Masuk" button
- Show "Good Evening,Jonathan" in Home Page

B. Negative Testing :
1. Input incorrect password with proper email :
  - Open Browser
  - Navigate to hadirr.com
  - Click 'Masuk' button
  - Key in email (percob*****yy@gmail.com)
  - Key in password (12******)
  - Click "Masuk" button
  - Show "Incorrect username or password"
  
2. Input blank email & password :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Masuk" button
  - Click "Masuk" button without key in email & password
  - Show "email can't be blank" and "password can't be blank"

3. Login in different browser at the same time :
  - Open 2 browser (example : Chrome and Firefox)
  - Navigate to hadirr.com for each browser
  - Click "Masuk" button
  - Key in email and password in both browser
  - Click "Masuk" button in both browser
 
 Sign Up :
 A. Positive Testing :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Daftar" button
  - Key in all form with correct data
  - Thick the "Syarat & Ketentuan"
  - Click "Buat Akun" button
  - Show "Good Evening, ..." in Home Page
 
 B. Negative Testing :
  1. Input email with disposable email or temporary email :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Daftar" button
  - Key in all form, but for email form need to input testinghadirr@getnada.com
  - Thick the "Syarat & Ketentuan"
  - Click "Buat Akun" button
  - Show error message for invalid email
  
  2. Blank form :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Daftar" button
  - Let the form blank
  - Click "Buat Akun" button
  - Show error message for each text field (from top to bottom)
  
  3. Fill the form but doesn't thick the "Syarat & Ketentuan" :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Daftar" button
  - Key in the form with correct data
  - Don't thick the "Syarat & Ketentuan"
  - Click "Buat Akun" button
  - Show message required field for "Syarat & Ketentuan" 
  
  Sign Up Free Trial :
  A. Positive Testing :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Coba Hadirr Gratis" button
  - Key in all form with correct data
  - Click "Daftar Akun Free Trial" button
  - Show "Good Evening" in Home Page
  
  B. Negative Testing :
  1. Blank form :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Coba Hadirr Gratis" button
  - Ignore the form
  - Click "Daftar Akun Free Trial" button
  - Show required field message for each field
  
  2. Input email with disposable email or temporary email :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Coba Hadirr Gratis" button
  - Key in all the form with correct data but for the email, use testinghadirr@getnada.com
  - Thick the "Syarat & Ketentuan"
  - Click "Daftar Akun Free Trial" button
  - Show invalid email message for email field

  3. Input dummy phone number :
  - Open Browser
  - Navigate to hadirr.com
  - Click "Coba Hadirr Gratis" button
  - Key in all the form with correct data but for the phone number, use +62878910324
  - Thick the "Syarat & Ketentuan"
  - Click "Daftar Akun Free Trial" button
