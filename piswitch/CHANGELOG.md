# Changelog

## 0.2.1

- Fix HA ingress: root path now correctly rewrites base href for sidebar

## 0.2.0

- Merged frontend + backend into single Go binary (no more Node.js)
- Added MQTT configuration options (broker, username, password, client_id)
- Persistent board config data in /config/piswitch/
- Plain-text console logging for HA log viewer

## 0.1.0

- Initial release
- Serves PiSwitch frontend as a Home Assistant add-on
- Supports ingress for seamless HA sidebar integration