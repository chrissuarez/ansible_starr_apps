# Ansible Starr Apps

Installs

- Radarr
- Sonarr
- Sabnzbd
- Notifarr
- Watchtower
- Emby


Make sure to have .vault_key in the root of the user directory

https://drive.google.com/file/d/1SzJ4i4qODXm9pK1EFCQzQXllx-Wia0lf/view?usp=sharing

create a creds file: /etc/sbmcredentials

https://drive.google.com/file/d/17pS3NRPu3mXCTcOrXQHWtjgDRqFcVl6W/view?usp=drive_link


Run with
sudo ansible-pull -U https://github.com/chrissuarez/ansible_starr_apps.git local.yml
