# Enrolment & Platform SSO: What's new for '26?

_by **Armin Briegel** and **Thomas Ortscheid**_

## Jamf Setup Manager

- Startup taking more time because of additional pSSO and DDM options in macOS 26
- **WebHooks**: e.g. send messages to Mattermost when Setup Manager has finished
  - Setup Manager HUD: Can display statistics based on WebHooks ← <span style="color:red">_add link here_</span>

### Managed Migration Assistant

- Will be available as Blueprint soon

## Platform SSO

- Based on _**SSO Extension**_ since macOS 10.15 (Catalina)
- _**Platform SSO**_ since macOS 14 → SSO right on the login stage
  - Downside: Probably still asks for login multiple times
- _**Platform SSO during ADE**_ since macOS 26
  - Works with:
    - Okta Verify
    - Entra ID Company Portal
    - Twocanoes XPSSO
    - Keycloak

## Setup Checklist

- Essentially a customizable welcome screen
- Can be used to further customize things after login, e.g.:
  - Browser
  - Mail Setup
  - Microphone and Camera access
