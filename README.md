# vncauto

This repo contains `vnc` bash script file.  

# Purpose

- Get LAN IPv4 automatically.
- Kill the first 10th old vnc instances automatically.
- Remove old vnc server caches.
- Inject `startxfce4 &` command to `"~/.vnc/xstartup"` file (if not yet) in order to start vnc server with default xfce4 session.
- Start new vnc server instances for different screen sizes automatically.
- Show the newly started vnc server instance addresses to the user.

# TODO

- You have to install `tightvncserver` and `xfce4` by yourself to use this `vnc` script.
- Move this `vnc` bash script file into your favorite executable directory. (example: `/usr/bin` or `~/.local/bin`)
