# HTML Authentication POC

This project is a simple authentication flow created using only HTML.  
It demonstrates how different pages can be connected using anchor tags for navigation.

No CSS or JavaScript has been used in this project. The focus is purely on HTML structure and page redirection.

---

##  Pages Included

- login.html – User login page  
- register.html – New user registration page  
- forgot-password.html – Page to request password reset  
- reset-password.html – Page to set a new password  
- dashboard.html – Simple dashboard after login  

---

## How Navigation Works

All redirections between pages are handled using `<a>` (anchor) tags.  
For example:
- Login redirects to the dashboard
- Register redirects back to login
- Forgot password redirects to reset password
- Dashboard includes a logout link that redirects to login

---

##  Purpose

This project was created as a basic Proof of Concept (POC) to understand:
- HTML page structure
- Forms in HTML
- Linking multiple pages together
