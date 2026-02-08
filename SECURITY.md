# Security Policy

## Reporting Security Vulnerabilities

We take the security of SiliconFlow projects seriously. If you discover a security vulnerability, please report it to us responsibly.

### How to Report

📧 **Email**: security@siliconflow.com

Please include as much information as possible:

* Description of the vulnerability
* Steps to reproduce
* Affected versions
* Potential impact
* Suggested fix (if any)

### What Happens Next

1. We will acknowledge receipt of your report within 48 hours
2. We will investigate the issue and determine the severity
3. We will work on a fix and notify you when it's ready
4. We will coordinate disclosure with you
5. Once the fix is deployed, we will credit you in the release notes (with your permission)

### What to Expect

* We appreciate responsible disclosure
* We will work with you to understand and fix the issue
* We will keep your identity confidential (unless you want credit)
* We will update you on our progress

## Security Best Practices

### For Users

* **Keep dependencies updated** - Regularly update to the latest stable versions
* **Review code changes** - Review pull requests before merging
* **Use secure configurations** - Follow security best practices in your setup
* **Monitor for vulnerabilities** - Use tools like Dependabot to detect vulnerabilities

### For Contributors

* **Follow secure coding practices** - Use established security patterns
* **Sanitize user input** - Always validate and sanitize input data
* **Use HTTPS** - Enforce HTTPS for all communications
* **Keep secrets secure** - Never commit secrets or API keys
* **Review dependencies** - Be aware of the security of third-party dependencies

### For Maintainers

* **Enable security features** - Use GitHub security features (Dependabot, code scanning)
* **Review dependencies regularly** - Keep third-party libraries updated
* **Use branch protection** - Require reviews for code changes
* **Monitor for vulnerabilities** - Actively monitor security advisories

## Supported Versions

Security updates will be provided for the following versions:

| Version | Support Status |
|---------|----------------|
| Latest | :white_check_mark: Actively supported |
| Previous | :white_check_mark: Security fixes only |
| Older | :x: No longer supported |

## Security Advisories

We will publish security advisories for:

* Critical vulnerabilities (CVSS 9.0+)
* High severity vulnerabilities (CVSS 7.0-8.9)
* Medium vulnerabilities (CVSS 4.0-6.9) if widely used

Subscribe to releases to receive security notifications.

## Third-Party Dependencies

We use various third-party dependencies. We aim to:

* Keep them updated to the latest secure versions
* Regularly scan for known vulnerabilities
* Respond promptly to CVE reports
* Provide guidance on updating

## Additional Resources

* [GitHub Security Advisories](https://github.com/siliconflow-community/security/advisories)
* [GitHub Documentation - Security](https://docs.github.com/en/code-security)
* [OWASP Top 10](https://owasp.org/www-project-top-ten/)

## Contact

For non-critical security questions, feel free to:

* Open a discussion on GitHub
* Join our [Discord](https://discord.gg/3nAMSVJekY)
* Email community@siliconflow.com

Thank you for helping keep SiliconFlow projects safe! 🛡️
