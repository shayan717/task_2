# Single Sign-On (SSO) and OAuth 

## What is SSO?

**Single Sign-On (SSO)** is an authentication process that allows a user to access multiple applications with one set of login credentials like email and password. Instead of logging into each service separately, SSO enables centralized login, improving user experience and reducing password fatigue.

### Example:
- Logging into Gmail automatically grants access to Google Drive, YouTube, Facebook  without re-entering credentials.

## What is OAuth?

**OAuth (Open Authorization)** is a standard protocol that allows one application to access resources or user data from another service (the provider) **without sharing the user's password**. OAuth is often used to implement SSO.

### How OAuth Works Simplified Flow:
1. User clicks "Sign in with Google".
2. App redirects user to Google OAuth server.
3. User logs in and grants permission.
4. Google sends back an **authorization code**.
5. App exchanges this code for an **access token**.
6. App uses the token to access user's info (like email) securely.

## SSO and OAuth Together

OAuth is a common framework used to implement SSO. By using OAuth-based SSO, users can authenticate once (e.g., with Google ) and access multiple applications without logging in again.

**Benefits of SSO:**
- Easier login experience.
- Reduces the number of passwords.
- Centralized authentication improves security.

**Common SSO Providers:**
- Google
- Facebook
- LinkedIn
- Microsoft

