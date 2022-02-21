# Example of protected routes

- Example of protected routes using react router dom version 6.
- Uses a fake useAuth hook to determine user's auth status.
- Have 4 public components (Nav, Home, Pricing, and Login) and 2 private components (Dashboard and Settings).
- When a user who isn't authenticated tries to go to '/dashboard' or '/settings', they're redirected to '/login'
- Once they login, we redirect them back to '/dashboard' by default or to '/settings' using user's location they were trying to visit