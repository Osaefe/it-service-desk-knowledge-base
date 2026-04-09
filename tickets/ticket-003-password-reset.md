# Ticket 003: Password Reset & Account Lockout

## Summary
User account locked due to multiple failed login attempts.

## Symptoms
- Cannot log into Office 365 / Windows  
- Error: “Account locked”  

## Investigation
- Verified account status in Active Directory  
- Checked last login attempts  
- Confirmed temporary lockout  

## Root Cause
User forgot password and exceeded login attempts  

## Resolution
- Reset password in AD  
- Communicated new password securely  
- User able to log in  

## Outcome
Access restored; incident documented per service desk protocol.
