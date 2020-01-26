# mate-next-overlay
Gentoo Mate Next Overlay With Development Branch Ebuilds. \

- Current Version = 1.23.3 

How To Use This Un-Official Gentoo Mate-Desktop Overlay ? \
As Root - Go To /usr/local And Clone This Git Repo And = \
git clone https://github.com/javashin/mate-next-overlay.git -b master mate-next-overlay \
Then Inside /usr/local/mate-next-overlay Copy mate-next-overlay.conf to /etc/portage/repos.conf/ \
emerge --sync. 

To Install = \
emerge -av mate-base/mate \
To Upgrade Existing Mate-Desktop Installation = \
emerge --deep --update --newuse --with-bdeps=y --verbose --ask @world 



# JavaShin-X. 2020.
 
