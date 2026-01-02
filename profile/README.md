# Rumba

A self-hosted identity platform that serves as an alternative to Microsoft Entra ID and
Azure AD.

## What Rumba Does

Rumba provides identity management for organizations that need control over their
authentication infrastructure. Written in Rust, it implements standard protocols for
compatibility with existing systems.

### Implemented Features

- **OAuth 2.0 / OpenID Connect** - Authorization code, device flow, on-behalf-of, and
  service-to-service flows
- **Microsoft Graph API** - 114+ endpoints for users, groups, applications, and directory
  management
- **SCIM 2.0** - User and group provisioning (RFC 7643/7644 compliant)
- **Multi-tenant architecture** - Domain-based tenant isolation with PostgreSQL storage
- **MFA** - TOTP, HOTP, push notifications, backup codes
- **Audit logging** - Immutable event trails
- **Admin interface** - Web-based tenant management

### In Development

- NSS/PAM modules for Linux authentication
- Container images and Helm charts
- WebAuthn/FIDO2 support
- LDAP server
- Kerberos KDC
- Group Policy distribution
- Windows domain join

## Target Users

- **Himmelblau users** - Linux authentication with Entra ID compatibility
- **Government agencies** - Data residency and sovereignty requirements
- **Enterprises** - Self-hosted identity without vendor lock-in
- **Homelab users** - Learning and development environments

## Project Status

Internal development has concluded. The project is now being released publicly at
[rumba-id/rumba.id](https://github.com/rumba-id/rumba.id).

## License

Rumba uses the [Functional Source License (FSL)](https://fsl.software/). Each version
converts to Apache 2.0 or MIT two years after release.

## Links

- [Main Repository](https://github.com/rumba-id/rumba.id)
- [Himmelblau IDM](https://himmelblau-idm.org/)

## Contact

- Email: <hello@rumba.id>
