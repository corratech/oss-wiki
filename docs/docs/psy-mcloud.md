# Psychedelic Magento Cloud

Adobe Commerce Cloud formerly known as Magento Cloud is a Platform as a Service (PaaS) environment for magento 2x family of ecommerce framework. The "Psychedelic MCloud" is a group of custom scripts created in bash to enable, history, tmux integration etc.

## Details

Psychedelic MCloud contains customizations for:

- bash history
- tmux integration
- mysql backups
- ngrok integration (partial)

### Bash

The bash customization is for enabling bash history, when invoked from the terminal multiplexer (tmux).

### tmux

The tux customization contains the basic `tmux.conf` file and a custom `shell` to enable bash overrides.

The `tmux.conf` try to use a custom shell from the file `shell` from the above bash bash customization.
The `tmux.conf` also have support for mouse support for various versions of tmux found in new-generation and old-generation cloud servers.

### MySQL Scripts

There are two mysql customizations in this directory.
The `myconnect` is used to connect to mysql by directly reading `app/etc/env.php`.
Also `mydbdump` is a mysql backup script.

### ngrok

This is used for media sync using ngrok
