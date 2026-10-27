# Experiment: SQL Injection

## Aim
To understand SQL injection using a deliberately vulnerable local application.

## Requirements
- A deliberately vulnerable local application
- A local test database
- Access to the application's source code or lab instructions

## Theory
SQL injection occurs when untrusted input is incorporated into SQL
queries in an unsafe manner. Parameterized queries and appropriate
database permissions are key mitigations.

## Procedure
1. Start the designated vulnerable application locally.
2. Identify the lab's input field that interacts with a database.
3. Submit ordinary test input and observe the response.
4. Follow the lab's supplied test cases in the isolated environment.
5. Review the corresponding query construction in the source code.
6. Replace unsafe query construction with parameterized queries.
7. Repeat the test cases to verify the fix.

## Observations and Output
- Application and database:
- Input field tested:
- Behavior before remediation:
- Parameterized-query changes:
- Behavior after remediation:

## Result
SQL injection risks and the use of parameterized queries were studied in a controlled lab.

## Precautions
- Never test a third-party database without explicit authorization.
- Use dummy data in an isolated environment.
- Do not extract, alter, or delete real records.

## References
- [Official Kali Linux documentation](https://www.kali.org/docs/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

