# Ansible Role: Mailhog

Installs and configures Mailhog server for testing emails. PHP server sending out emails will need to update its php.ini file to direct sendmail cia mhsendmail(included with mailhog now).

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    mailhog_release_url: https://github.com/mailhog/MailHog/releases/download/v1.0.0/MailHog_linux_amd64
    mailhog_install_path: /usr/local/bin/mailhog
