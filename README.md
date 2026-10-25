# Probrofinity VIP System

VIP license configuration for Probrofinity Android applications.

## Repository Files

- config.json: System configuration
- keys.json: VIP license records
- devices.json: Device restrictions

## Supported License Types

- 7_days
- 30_days
- lifetime

## License Rules

- Expired licenses must not activate VIP.
- Revoked licenses must be rejected.
- Invalid keys must be rejected.
- Offline access is limited to previously verified licenses.
- User application data must not be deleted when a license expires.
- A new valid license must reactivate VIP without requiring an app update.

## Security

- Keep this repository private.
- Never embed GitHub access tokens in an APK.
- Do not treat local JSON files as secure authentication.
- Use a trusted verification backend for online license validation.

## Project

Probrofinity VIP Key System
