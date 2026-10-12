# Repository Purpose and Public Visibility

- This repository has one purpose: host JSON files containing URLs and titles for the app-switcher widget used across Devyce internal apps. Consuming apps infer icon locations from the services' base URLs; do not add icon fields to the JSON.
- Everything in this repository is public. Treat every file and change as publicly accessible, even though the consuming apps are internal.
- Never add secrets, credentials, tokens, private keys, personal data, or confidential internal information. Check URLs for embedded credentials, sensitive query parameters, and information that is not approved for public disclosure.
- Keep changes focused on the JSON link data and the minimal supporting documentation needed to maintain it.