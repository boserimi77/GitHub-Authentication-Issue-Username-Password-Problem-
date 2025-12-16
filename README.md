# GitHub-Authentication-Issue-Username-Password-Problem-
# GitHub Auth Issue

Problem: `git push` kept asking for username/password.

Cause: Repo used HTTPS; GitHub no longer supports passwords.

Fix: Switched to SSH authentication.

Steps: Generate SSH key → add to GitHub → update remote to SSH.

Result: Secure, password-free pushes.

Author: boserimi1995

