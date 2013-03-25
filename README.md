gentoo-proxy-maintenance-webdavcgi
==================================

Repo to track my proxy maintainers work against Gentoo for webdavcgi (and deps)

To use this repo:

1. Install and setup layman
2. `cd /etc/layman/overlays`
3. `wget https://raw.github.com/dev-zero/gentoo-proxy-maintenance-webdavcgi/master/layman/proxy-maintenance-webdavcgi.xml`
4. `sed -i -e 's|^#overlay_defs|overlay_defs|' /etc/layman/layman.cfg`
5. `layman -S`
6. `layman -a proxy-maintenance-webdavcgi`
7. `emerge webdavcgi`
