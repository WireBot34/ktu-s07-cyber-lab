# Experiment: Authentication and Authorization Testing

## Aim
To understand how authentication and authorization controls are assessed in a lab.

## Requirements
- A local test web application with multiple test accounts
- Browser developer tools
- Permission to test the application

## Theory
Authentication verifies a user's identity. Authorization determines
which resources and actions that identity may access. Both controls
must be enforced by the server.

## Procedure
1. Create or open the designated lab application.
2. Sign in using an authorized test account.
3. Identify the application's protected pages and functions.
4. Verify that unauthenticated requests are denied access.
5. Compare access for test accounts with different roles.
6. Check that logging out invalidates the applicable session.
7. Record expected and actual access-control behavior.

## Observations and Output
| Test | Expected behavior | Actual behavior |
|---|---|---|
| Access without login | Denied | |
| Access permitted resource | Allowed | |
| Access restricted resource | Denied | |
| Use session after logout | Denied | |

## Result
Authentication and authorization behavior was examined using designated test accounts.

## Precautions
- Use only designated accounts.
- Do not access another person's data.
- Never record real passwords or session tokens in the report.

## References
- [Official Kali Linux documentation](https://www.kali.org/docs/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

