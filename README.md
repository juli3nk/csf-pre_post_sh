# ConfigServer Security & Firewall (CSF) – csfpre.sh / csfpost.sh

Installs a pre- and a post script for the CSF firewall that will be executed on every (re-)start.

## Installation

Installation is quite straightforward. Remember to execute most of these commands with admin privileges (`sudo su`):

```
# Clone repo and start installation
$ cd /usr/local/src
$ git clone https://github.com/juliengk/csf-pre_post_sh.git
$ cd csf-pre_post_sh
$ ./install.sh

# Restart CSF
$ csf -ra
```

## User Feedback
### Issues

If you have any problems with or questions about this image, please contact us through a [GitHub](https://github.com/juliengk/csf-pre_post_sh/issues) issue.

