# Betty Installation
This directory contains my betty installation.

Learn more about betty [HERE](https://dev.to/angelotheman/the-art-of-clean-code-mastering-the-betty-style-30mo)

## Installation

1. Clone this repo
```
git clone https://github.com/developer-system-config.git
```

2. `cd` into the betty installation directory
```
cd betty-installation
```

3. Install the linter with 
```
sudo ./install.sh
```

4. Change the permissions of the Betty file in the directory
```
chmod a+x betty
```

5. Move the `betty` file into `/bin/`
```
sudo mv betty /bin/
```

You can now type `betty <filename>` to run the Betty linter!

This would check for both `betty-style` and `betty-docs`

Happy Coding 🚀
