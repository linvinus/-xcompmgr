xcompmgr
========

Package for ubuntu but sources also can be used in other distros.

As for me, it faster than compton, tested with open source radeon driver.

recommended options:
`xcompmgr -l -5 -t -5 -r 4 -cC -V -b`

compiled package for ubuntu available there https://launchpad.net/~linvinus/+archive/linvinus

Main changes:
 * Ported, from compton, sync to vblank (using DRM VBlank ioctl) (first time this method was implemented in Mythtv)
 * don't draw shadow for metacity alt+tab frames
 * Option to Daemonize/background process
