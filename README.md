# Unraid Docker Template for Papra

This repository contains a custom Community Applications template for running **[Papra](https://github.com/papra-hq/papra)** on Unraid.

## Template Details

- **Docker Image:** `ghcr.io/papra-hq/papra:latest`
- **WebUI:** `http://[IP]:[PORT]`
- **Persistent Data:** `/mnt/user/appdata/papra`
- **Ports:** 1221 (configurable)
- **PUID / PGID:** 99 / 100 (default, configurable)

## Installation

1. Copy the `Papra.xml` template into your Unraid `templates-user` folder.
2. Open Community Applications and install Papra using the template.
3. Make sure the following folders exist (or are mapped correctly in the template):
   - `/mnt/user/appdata/papra/db`
   - `/mnt/user/appdata/papra/documents`
4. Configure the **App Base URL**, port, and storage paths as needed.

## Notes

- You can use a local IP or a reverse proxy / domain name for the **App Base URL**.
- The template includes an icon and default configuration suitable for most setups.

## License

See Papra’s repository for licensing information.
