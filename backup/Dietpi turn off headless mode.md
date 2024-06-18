"Re-enabling HDMI requires a reboot. If you need emergency HDMI output, edit the following files on first partition of the SDcard from external system:

In config.txt, set “hdmi_ignore_hotplug=0” and comment/remove all (max_)framebuffer_(width/height) lines.
In dietpi.txt, set “AUTO_SETUP_HEADLESS=1”."
 