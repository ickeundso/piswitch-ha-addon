# PiSwitch Home Assistant Add-on

## Overview

This add-on serves the PiSwitch frontend as a panel in your Home Assistant sidebar. It connects to your existing PiSwitch backend running on the network.

## Configuration

### `backend_url`

The URL of your PiSwitch backend API, e.g., `http://192.168.1.100:3000`.

### `ws_enabled`

Enable or disable WebSocket connections for real-time switch state updates.

## Usage

1. Install the add-on from the Add-on Store
2. Set the `backend_url` to point at your PiSwitch backend
3. Optionally enable `ws_enabled` for real-time updates
4. Start the add-on
5. Click "PiSwitch" in the Home Assistant sidebar