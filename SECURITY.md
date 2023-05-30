
# Security Policy
## Reporting Security Issues
We take security seriously at Autovant.io. We appreciate your efforts in responsibly disclosing any security vulnerabilities you may find. To report a security issue, please email us at security@autovant.io. We will review and respond to your report as quickly as possible.

Please provide detailed information about the vulnerability, including:

Description of the vulnerability
Steps to reproduce the vulnerability
Any supporting materials, such as proof-of-concept code or screenshots
Your contact information (name, email address, etc.)
We kindly request that you do not publicly disclose any potential vulnerabilities until we have had an opportunity to review and address the issue.

Supported Versions
Autovant.io is a car rental project developed by Rupesh Sharma. The following versions of the project are currently supported with security updates:
| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.1.x   | :white_check_mark: |
| 5.1.x   | :white_check_mark: |
| 5.1.x   | :white_check_mark: |

Please ensure that you are using one of the supported versions to receive the latest security updates. It is highly recommended to keep your project up to date with the latest release.

Security Best Practices
To enhance the security of Autovant.io, we recommend following these best practices:

Regularly Update Dependencies: Keep your project's dependencies up to date with the latest security patches. Use dependency management tools, such as npm or Composer, to automatically check for updates and apply them.

Secure Authentication: Implement secure authentication mechanisms, such as password hashing, multi-factor authentication (MFA), or OAuth, to protect user accounts and prevent unauthorized access.

Input Validation: Validate and sanitize all user input to prevent common web vulnerabilities, such as cross-site scripting (XSS) and SQL injection attacks. Utilize secure coding practices and frameworks that provide input validation mechanisms.

Protection against Cross-Site Request Forgery (CSRF): Implement CSRF tokens or other protective measures to prevent attackers from exploiting cross-site request forgery vulnerabilities.

Secure Session Management: Ensure that session management is implemented securely. Use secure cookies, enforce strong session expiration policies, and protect session identifiers from being leaked or stolen.

Prevent Information Disclosure: Avoid exposing sensitive information, such as error messages, stack traces, or configuration files, to end-users. Properly handle exceptions and error conditions without revealing internal system details.

Secure Communication: Utilize secure communication protocols (HTTPS/TLS) to encrypt network traffic and protect data transmission between clients and servers.

Access Control and Authorization: Implement proper access controls and authorization mechanisms to ensure that users can only access resources and perform actions they are authorized to.

Regularly Backup Data: Maintain regular backups of your data to prevent loss or damage in case of a security incident or system failure.

Security Updates and Patching
Autovant.io project team is committed to addressing security vulnerabilities in a timely manner. When security issues are reported or discovered, we will investigate and develop patches or updates as necessary.

Security updates will be released as new versions. It is highly recommended to subscribe to the project's repository or mailing list to receive notifications about new releases and security patches.

Please note that support for older versions may be limited, and it is important to upgrade to the latest supported version to ensure the best security posture.

Bug Bounty Program
At this time, Autovant.io does not
