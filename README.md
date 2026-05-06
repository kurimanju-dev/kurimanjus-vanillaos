# Custom Vib Image (with Tailscale AND DisplayLink)

This custom image is based on the official VanillaOS image and has Tailscale as well as the DisplayLink driver built in. Use the host shell to access the `tailscale` command. DisplayLink on Linux is unstable and may cause stability issues. Use this image **ONLY** if you really **NEED** DisplayLink!

## Use the custom image

You can then point ABRoot to the custom image to use it.

- Edit the configuration file with the command: `abroot config-editor`.
- Change the "name" entry from something like `vanilla-os/desktop` to `kurimanju-dev/kurimanjus-vanillaos` [**Note**: All characters must be in lowercase.]
- Change the "tag" entry from `main` to `displaylink`.
- Now, Run `abroot upgrade` to switch to the custom image.
