# Experiment: Hydra

## Aim
To understand password-auditing concepts using a controlled authentication lab.

## Requirements
- An isolated local authentication service
- A designated test account
- Hydra installed in the lab environment
- Explicit authorization for all tests

## Theory
Hydra is a network login auditing tool that supports multiple
authentication services. Password audits should use a controlled
target, approved test accounts, and a small, authorized test dataset.

## Procedure
1. Start the isolated authentication lab.
2. Verify connectivity to the designated service.
3. Review Hydra's help output:
   ```bash
   hydra -h
   ```
4. Read the documentation for the relevant service module.
5. Follow the instructor-approved exercise using only the lab account
   and the supplied test credentials.
6. Record the service response and relevant security controls.
7. Recommend protections such as strong passwords, rate limiting,
   account lockout where appropriate, and multifactor authentication.

## Observations and Output
- Lab service:
- Test account identifier:
- Authentication controls observed:
- Rate limiting or lockout behavior:
- Recommendations:

## Result
Password-auditing concepts and defensive authentication controls were studied.

## Precautions
- Never run password attacks against public or third-party systems.
- Use only instructor-provided test accounts and credentials.
- Avoid exposing passwords or authentication logs in the report.

## References
- [Official Kali Linux documentation](https://www.kali.org/docs/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

