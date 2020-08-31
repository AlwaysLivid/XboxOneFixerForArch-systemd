# XboxOneFixerForArch-systemd

This tool automates the Bluetooth configuration process described in the [Arch Linux Wiki](https://wiki.archlinux.org/index.php/Gamepad#Connect_Xbox_Wireless_Controller_with_Bluetooth) for connecting the Xbox One controller on Arch Linux-based operating systems (and others).

## Installation

### Simple installation

- Ensure that you're currently logged in as a user with root access, or that you're able to use the `sudo` command.
- Run the following command:

```sh
curl https://raw.githubusercontent.com/AlwaysLivid/XboxOneFixerForArch-systemd/master/xboxfixer.service > /etc/systemd/system/xboxfixer.service
```

Make sure to prepend `sudo` if you're not logged in as a user with root access.

### Hard installation

- Create a new file in your `systemd` service directory.

```sh
nano /etc/systemd/system/xboxfixer.service
```

- Copy the contents of the file `xboxfixer.service`.

**Alternatively, just run the following in order to copy and paste the file in the appropriate directory:**

`cp xboxfixer.service /etc/systemd/system`

Make sure to prepend `sudo` if you're not logged in as a user with root access.
