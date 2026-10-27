# Experiment: Recon-ng

## Aim
To perform authorized open-source intelligence (OSINT) reconnaissance using Recon-ng.

## Requirements
- Kali Linux or another compatible Linux distribution
- Recon-ng
- Internet connection
- An authorized domain or a local lab target

## Theory
Recon-ng is a modular reconnaissance framework used to collect publicly
available information about domains and related assets. It provides
workspaces, modules, a database, and reporting features.

## Procedure
1. Install Recon-ng using the official installation instructions.
2. Start the framework:
   ```bash
   recon-ng
   ```
3. Create a dedicated workspace:
   ```text
   workspaces create ktu_lab
   ```
4. Display available commands:
   ```text
   help
   ```
5. Inspect available marketplace modules:
   ```text
   marketplace search
   ```
6. Read a module's documentation before installing or running it.
7. Select only modules appropriate for your authorized lab target.
8. Review the collected records using the relevant database commands.
9. Export the results using the framework's supported reporting features.

## Observations and Output
Record the following after performing the experiment:

- Workspace created:
- Modules examined:
- Authorized target:
- Records collected:
- Export format:
- Screenshots or output:

## Result
Recon-ng was studied and used to organize authorized reconnaissance findings.

## Precautions
- Obtain permission before conducting reconnaissance.
- Use only approved domains and targets.
- Protect collected personal and organizational information.
- Module names, dependencies, and commands may vary by version.

## References
- [Official Kali Linux documentation](https://www.kali.org/docs/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

