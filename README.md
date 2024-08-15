# Syncthing Integration with Home Assistant

Syncthing is a continuous file synchronization program. It synchronizes files between two or more computers in real-time, safely protected from prying eyes.

## Features
The Syncthing integration adds one sensor per syncing folder.

## Monitoring and Setup
The Syncthing integration allows you to monitor states of your synced folders from within Home Assistant and to set up automations based on the information.

### Prerequisites
To set up the monitoring, you need to get an API key. Open the Syncthing web interface (e.g., `http://127.0.0.1:8384`) in the browser and go to `Actions > Settings`. You will find the key on the right of the settings dialog.

## Installation
1. Install this integration using [HACS](https://hacs.xyz/) by [adding this repository](https://hacs.xyz/docs/faq/custom_repositories) or manually copy the files to your Home Assistant installation.
2. Restart Home Assistant to load the integration.

## Configuration
After installation, search and add component Comwatt in Home Assistant integrations page.

Or click [![Configuration](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start?domain=comwatt)

#### Manual Configuration Steps
If the above My button doesn't work, you can also perform the following steps manually:

1. Browse to your Home Assistant instance.
2. Go to `Settings` > `Devices & Services`.
3. In the bottom right corner, select the `Add Integration` button.
4. From the list, select `Syncthing`.
5. Follow the instructions on screen to complete the setup.

### Entities
The Syncthing integration adds one sensor per syncing folder.
