Secure Login System by Riya Khatri
Python-based secure login system using bcrypt for hashing, regex for validation, and logging for activity tracking.
Features:
 * Secure Passwords: bcrypt hashed storage.
 * Input Validation: Username/password checks.
 * Activity Log: login_activity.log for all attempts.
Security:
Enhanced security by avoiding plain text passwords and validating inputs, unlike insecure systems.
Usage:
Run secure_code_review.py, then enter credentials.
Sample Output:
---- Secure Login ----
Enter username: admin
Enter password: admin123
Login successful!

Known Issues & Improvements (Bandit Report):
 * Hardcoded Passwords: High-severity risk (admin123, password1).
 * input() Use: Medium-severity concern.
