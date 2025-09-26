> Export your localStorage library for https://anttikotajarvi.github.io/modbus-webui (old url) to https://modbuswebui.dev (new url).




Since switching to a custom domain (26.9.2025) users havent been able to directly access their locally stored library from under the new domain.

This is a tool for easily copying the library from under the old domain to the new one.

## How
Download or copy from: \
https://anttikotajarvi.github.io/modbus-webui-legacy-export

Or direct import by:
- Going to https://modbuswebui.dev
- Navigating to ´Import/Export´
- Open popup with ´Get localStorage from old domain´


## Why
Local storage is per domain origin, and since this is hosted under the same root as the old one -> the same storage is still accessible from here.

Moving into modbus-webui 1.0.0 we aim minimize the need for these kinds of interruptions in the deployed build of the app.
