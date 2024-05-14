# THIS ROLE DOSE NOT WORK!
I don't get the docker container running. I'm not sure if it is a permission error, or due to the fact, that I bind /etc to /mash/wallabag/config/etc because the container needs to write config files there.

If somebody has an idea, I'm happy to accept a PR and to reopen this PR! 😀

# Ansible Role for Wallabag

This role is created for the [MASH playbook](https://github.com/mother-of-all-self-hosting/mash-playbook). It is inspired by the following projects:

- [Mother of All Self Hosting - GotoSocial Role](https://github.com/mother-of-all-self-hosting/ansible-role-gotosocial)
- [Mother of All Self Hosting - Gitea Role](https://github.com/mother-of-all-self-hosting/ansible-role-gitea)

## Description

This role installs and configures Wallabag, a self-hosted application for saving web pages to read them later. 
Find out more [on the Wallabag homepage](https://wallabag.org/).

This role is **not** affiliated with the Wallabag project.

## Role Variables

You can find all variables in [`defaults/main.yml`](https://github.com/Bergruebe/ansible-role-wallabag/blob/main/defaults/main.yml).
