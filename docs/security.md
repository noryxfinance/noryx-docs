# Noryx Security

Security is a core part of the Noryx Platform architecture.

Noryx Finance is designed to reduce unnecessary exposure of user credentials, exchange connections and sensitive operational data.

## Security Principles

The platform follows several general security principles:

- least-privilege access
- controlled authentication
- restricted credential handling
- encrypted communication
- separation of public and private infrastructure
- limited exposure of sensitive data
- operational monitoring

## Account Security

User accounts should be protected through mechanisms such as:

- secure authentication
- session controls
- password protection
- account access management
- multi-factor authentication where available

Users are responsible for protecting their own login credentials and devices.

## Exchange API Security

Exchange connections rely on API credentials generated directly by users on supported exchanges.

Recommended practices include:

- creating dedicated API credentials
- enabling only required permissions
- disabling withdrawal access whenever possible
- rotating credentials when necessary
- revoking credentials that are no longer required

Noryx should never request more exchange permissions than are necessary for the intended functionality.

## Credential Protection

Sensitive credentials should not be exposed in public interfaces, logs or documentation.

This includes:

- exchange API keys
- API secrets
- access tokens
- database credentials
- webhook secrets
- private infrastructure endpoints

Public documentation intentionally excludes the internal implementation of credential storage and secrets management.

## Encryption

Where technically applicable, communication between users, Noryx services and external providers should use encrypted connections.

Sensitive data should not be transmitted using insecure protocols.

## Infrastructure Access

Access to production infrastructure should be restricted to authorized systems and personnel.

Security controls may include:

- role-based access
- restricted administrative access
- environment separation
- secrets management
- activity logging
- service-level permissions

Exact production infrastructure details are intentionally not disclosed.

## Environment Separation

Where applicable, Noryx may separate environments such as:

- production
- development
- testing
- demo

This helps reduce the risk of development activity affecting live systems.

## Data Minimization

Noryx should collect and process only data necessary for platform functionality.

Sensitive data should not be publicly exposed or retained without a valid operational reason.

## Monitoring

The platform may monitor system health and operational events.

Monitoring can include:

- service availability
- authentication failures
- API connectivity
- execution failures
- infrastructure health
- abnormal system behavior

Public status information should remain aggregated and should not expose sensitive internal details.

## Logging

Logs may be used for operational monitoring, debugging and security analysis.

Logs should not intentionally expose:

- passwords
- API secrets
- private authentication tokens
- sensitive personal data
- full exchange credentials

## Third-Party Services

Noryx may rely on external service providers for infrastructure, authentication, billing, exchanges or other platform functions.

Third-party systems operate independently and may have their own security policies and availability constraints.

## User Responsibilities

Users should:

- use strong and unique passwords
- enable multi-factor authentication where available
- secure their exchange accounts
- review API permissions regularly
- revoke unused API credentials
- avoid sharing account access
- report suspicious activity

## Responsible Disclosure

If you believe you have identified a potential security vulnerability involving Noryx Finance, please contact:

security@noryxfinance.com

Please include:

- a clear description
- affected component
- reproduction steps
- expected impact
- supporting evidence where appropriate

Avoid:

- accessing unrelated user data
- disrupting production systems
- destructive testing
- public disclosure before investigation

## No Public Bug Bounty Guarantee

Noryx Finance does not guarantee financial compensation for vulnerability reports unless a formal bug bounty program is explicitly announced.

## Incident Response

If a security issue is identified, Noryx may take actions such as:

- restricting affected functionality
- rotating credentials
- disabling vulnerable integrations
- investigating system activity
- deploying remediation
- monitoring affected services

The exact response depends on the nature and severity of the issue.

## Public Information

For security reasons, Noryx does not publicly disclose:

- production network architecture
- credential storage implementation
- internal service addresses
- private API endpoints
- security-control configurations
- infrastructure secrets
- proprietary monitoring rules

## Privacy

For information regarding personal data handling, refer to the Noryx Privacy Policy.

Legal and privacy enquiries:

legal@noryxfinance.com

## Security Contact

security@noryxfinance.com

## Disclaimer

No software platform can guarantee absolute security.

Noryx Finance continuously aims to reduce security risk through controlled access, system monitoring and responsible infrastructure practices.
