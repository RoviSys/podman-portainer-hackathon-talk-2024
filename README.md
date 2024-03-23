# Podman & Portainer

## Podman Setup

1. Install Podman - https://podman-desktop.io/downloads/windows
   - Ensure you have WSL updated to the latest version (2.1.5.0)
   - [Notes](https://github.com/containers/podman/blob/main/docs/tutorials/podman-for-windows.md)
2. Run Docker Compose stack
   ```bash
   podman compose up -d
   ```
3. Navigate to http://localhost:9000 to view Portainer instance

## Portainer Setup

1. Navigate to http://localhost:9000
2. Create an admin user from the prompt
3. Select "Local" environment and connect
4. You should now be able to navigate throught he menus to see containers, images, networks, etc.
