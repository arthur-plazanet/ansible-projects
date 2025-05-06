# Ubuntu Server Setup

Basic initial setup for a new Ubuntu server, and install Nginx

## Steps

- Update packages
- Setup a firewall using UFW ([How to Set Up a Firewall with UFW on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-firewall-with-ufw-on-ubuntu)
  )
- Create a new user:
  - Add it to the `sudo` group
  - Add your current public SSH key to the new user's authorized keys
  - Generate a new SSH key for the new user
- Install Nginx
  - Create symbolic link between `sites-available` and `sites-enabled`
- SSH:
  - Disable root login
  - Disable password authentication

## Sources

- GitHub repo [WordPress Ansible](https://github.com/spinupwp/wordpress-ansible)
- [Initial Server Setup with Ubuntu](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu) and [How To Install Nginx on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-nginx-on-ubuntu-22-04#step-5-setting-up-server-blocks-recommended) from DigitalOcean
