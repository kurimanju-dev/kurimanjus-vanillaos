# Custom Vib Image (with Tailscale, Nvidia Version) - **UNTESTED!!**

This custom image is based on the official VanillaOS Nvidia image and has Tailscale built in. Use the host shell to access the `tailscale` command. Note: Since I do not own a device with an Nvidia GPU, this image is completely untested.

## Use the custom image

You can then point ABRoot to the custom image to use it.

- Edit the configuration file with the command: `abroot config-editor`.
- Change the "name" entry from something like `vanilla-os/desktop` to `kurimanju-dev/kurimanjus-vanillaos` [**Note**: All characters must be in lowercase.]
- Change the "tag" entry from `main` to `displaylink`.
- Now, Run `abroot upgrade` to switch to the custom image.
