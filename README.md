<h1>
  <img src="https://raw.githubusercontent.com/egnerdata/unraid-docker-templates/main/icons/papra.png" width="64" height="64" alt="Papra Icon" />
  Unraid Docker Template for Papra
</h1>

This repository contains a custom Community Applications template for running **[Papra](https://github.com/papra-hq/papra)** on Unraid.

## Template Details

- **Docker Image:** `ghcr.io/papra-hq/papra:latest`
- **WebUI:** `http://[IP]:[PORT]`
- **Persistent Data:** `/mnt/user/appdata/papra`
- **Ports:** 1221 (configurable)
- **PUID / PGID:** 99 / 100 (default, configurable)

## Installation

### Manual installation
1. Copy the `Papra.xml` template into your Unraid `templates-user` folder:  
   `/boot/config/plugins/dockerMan/templates-user/`
2. In the Unraid web UI, go to the **Docker** tab, click **Add Container**, and select **Papra** from the drop-down list.
3. Adjust settings such as **App Base URL**, port, and storage paths if needed.

> Note: Step 1 happen automatically when installing via Community Applications.

### Installation via Community Applications (recommended)
Once/if the template is accepted into CA, you can install Papra directly from Community Applications.  

> Note: All required folders and mappings will be created automatically regardless of installation method.

## Screenshots

![Papra dashboard](https://raw.githubusercontent.com/egnerdata/unraid-docker-templates/main/screenshots/papra-unraid_1.png)

![Papra container settings](https://raw.githubusercontent.com/egnerdata/unraid-docker-templates/main/screenshots/papra-unraid_2.png)

![Papra container](https://raw.githubusercontent.com/egnerdata/unraid-docker-templates/main/screenshots/papra-unraid_3.png)

## Notes

- You can use a local IP or a reverse proxy / domain name for the **App Base URL**.
- The template includes an icon and default configuration suitable for most setups.

## License

See Papra’s repository for licensing information.
