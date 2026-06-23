# Zero-Trust, Zero-Hassle: Rethinking Secure Access for Apple Fleets

_by **Craig Donovan**_

## Attestation examples

- **DeviceInformation** attestation, containing e.g.:
  - UDID
  - Serial Number
  - Software Update Device ID
- ACME device attestation ([acme-device-attest-01](https://datatracker.ietf.org/doc/draft-ietf-acme-device-attest/07/))
- Network Relay ([Apple Deployment Guide](https://support.apple.com/guide/deployment/use-network-relays-dep91a6e427d/web)), e.g. with Jamf Security Cloud
  - Natively built into Apple platforms
  - Zero-touch & pre-stage-ready micro-tunnels (because it is using built-in technology)
  - Strong sevice identity assertion
  - Ubiquitous network access
  - Co-exists with other VPNs on the same device
  - Device ID rather than User ID → Works with shared devices as well
