# Ansible Starr Apps

Installs

- Radarr
- Sonarr
- Sabnzbd
- Notifarr
- Watchtower
- Emby


Make sure to have <a "https://drive.google.com/file/d/1SzJ4i4qODXm9pK1EFCQzQXllx-Wia0lf/view?usp=sharing">.vault_key</a> in the root of the user directory

create a creds file: <a "https://drive.google.com/file/d/17pS3NRPu3mXCTcOrXQHWtjgDRqFcVl6W/view?usp=drive_link">/etc/sbmcredentials</a>


Run with
sudo ansible-pull -U https://github.com/chrissuarez/ansible_starr_apps.git local.yml
