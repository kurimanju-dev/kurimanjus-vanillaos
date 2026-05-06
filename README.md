# Custom Vib Image (with Tailscale)

This custom image is based on the official VanillaOS image and has Tailscale built in. Use the host shell to access the `tailscale` command.

## Use the custom image

You can then point ABRoot to your custom image to use it.

- Edit the configuration file with the command: `abroot config-editor`.
- Change the "name" entry from something like `vanilla-os/desktop` to `your-github-name/your-image-name` (for example `taukakao/custom`).  [**Note**: All characters must be in lowercase.]
- Now, Run `abroot upgrade` to switch to your custom image.
