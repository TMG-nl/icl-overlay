icl-overlay
===========

Gentoo overlay for ICL ebuilds

Using this overlay through layman:
----------------------------------
- "emerge layman"
- Edit the layman configuration "vi /etc/layman/layman.cfg" and add
  https://raw.github.com/hyves-org/icl-overlay/master/icl-overlay.xml
  to the 'overlay:' section.
- Now run "layman -a icl" to add the overlay
