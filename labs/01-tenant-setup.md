# Lab 01 - Microsoft Entra Tenant Setup

## Objective

Create a dedicated Microsoft cloud lab environment for hands-on Identity and Access Management practice while studying for the Microsoft SC-300 certification.

## Lab Environment

The environment was created using:

- Azure Free Account
- Microsoft Entra ID tenant
- Microsoft 365 E5 Trial
- Microsoft Entra ID P2 Trial

## Administrative Account

A dedicated cloud administrator account was created for lab administration.

Example account:

`sc300admin@clkgroup.onmicrosoft.com`

> The domain shown in this repository is fictional and does not represent the real lab tenant.

## Administrative Role

The SC300 Admin account was assigned the following role:

- Global Administrator

This account is used only for administrative lab activities.

## Licensing

The following trial licenses were enabled:

### Microsoft 365 E5

- 25 trial licenses available
- 1 license assigned to the SC300 Admin account

### Microsoft Entra ID P2

- 100 trial licenses available
- 1 license assigned to the SC300 Admin account

Microsoft Entra ID P2 provides access to advanced IAM capabilities used throughout the SC-300 labs, including:

- Conditional Access
- Privileged Identity Management
- Identity Protection
- Access Reviews

## Billing Safety

Recurring billing was disabled for both trial subscriptions.

The subscriptions remain available during the trial period and are configured not to automatically renew as paid subscriptions.

## Security Considerations

The following information is intentionally excluded from this repository:

- Real tenant domain
- Tenant ID
- Subscription ID
- Passwords
- Authentication tokens
- Payment information
- Personal identifiers
- MFA registration data

## Result

The Microsoft cloud lab environment is ready for SC-300 identity and access management exercises.

## Next Steps

Future labs will cover:

- User and group management
- Administrative roles
- MFA
- Conditional Access
- Identity Protection
- Privileged Identity Management
- Access Reviews
- Microsoft Graph
- PowerShell automation
