# Hermes Music Assistant App
A fork of the Music Assistant App for Home Assistant, customized with Hermes providers.

## About Music Assistant
Music Assistant is a free, open-source music library manager that connects to your streaming services and a wide range of connected speakers. Turn your Home Assistant instance into your own personal music streaming hub!

## Hermes Fork
This is a Hermes-branded fork with custom provider integrations including:
- ytmusic-free-provider for YouTube Music
- WebDAV and cloud filesystem providers

## Installation
1. Navigate to **Settings** → **Apps** → **App Store** in Home Assistant
2. Add the custom repository: `https://github.com/hermes-3640/home-assistant-addon-fork`
3. Search for "Hermes Music Assistant"
4. Click **Install**
5. Wait for the installation to complete
6. Click **Start**
7. Open the **Web UI** to set up Music Assistant

## Configuration
### Available Options
```yaml
log_level: info
safe_mode: false
```

## Data Storage
All Music Assistant data is stored within the App's data directory.

## License
Music Assistant is licensed under the Apache License 2.0.
