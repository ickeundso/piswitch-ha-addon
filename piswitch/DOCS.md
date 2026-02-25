# PiSwitch Home Assistant Add-on

## Overview

This add-on runs the PiSwitch IoT switch controller as a single Go binary inside Home Assistant. It serves the frontend, REST API, and WebSocket in one process — no separate backend needed.

## Configuration

### `mqtt_broker`

MQTT broker URL, e.g., `tcp://192.168.1.100:1883`.

### `mqtt_username`

Username for MQTT broker authentication.

### `mqtt_password`

Password for MQTT broker authentication.

### `mqtt_client_id`

Client ID for the MQTT connection (must be unique per broker). Defaults to `piswitch-ha`.

## Usage

1. Install the add-on from the Add-on Store
2. Configure the MQTT broker connection in the add-on settings
3. Start the add-on
4. Click "PiSwitch" in the Home Assistant sidebar

## Data Storage

Board configuration is stored in `/config/piswitch/` and persists across add-on updates.
