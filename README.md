# macOS Installers

This repository hosts macOS installation packages used by the IT Office for automated software deployment through Microsoft Intune.

## Available Installer

**Check Point Endpoint Security VPN E89.20**

The installer is stored as a GitHub Release asset:

`Endpoint_Security_VPN.dmg`

## Intune Deployment

Microsoft Intune uses a deployment script to download the installer from GitHub.

The original download URL remains operational following the repository's transfer to the IT-Office-Operations organisation.

## Important Notes

- **Keep this repository public** while Intune depends on unauthenticated downloads.
- Do not rename or delete release assets without reviewing the associated Intune deployment scripts.
- Test download URLs before making changes to releases or repository visibility.
- Installer updates should be tested before deployment to production devices.

## Ownership

Maintained by the IT Office under the **IT-Office-Operations** GitHub organisation.
