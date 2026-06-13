# Zybuntu Beta
This is just a debloated,better looking fork of Ubuntu
(still uses soystemD...)

nano ~/.config/fastfetch/config.jsonc

{
    "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",
    "logo": {
        "source": "/home/user/.config/fastfetch/Ascii.txt",
        "type": "file",
        "width": 5,
        "height": 5
    },
    "modules": [
        "title",
        "separator",
        {
            "type": "os",
            "format": "Zybuntu 1.2 LTS (Swift) x86_64"
        },
        "kernel",
        "uptime",
        "packages",
        "shell",
        "display",
        "de",
        "wm",
        "terminal",
        "cpu",
        "gpu",
        "memory"
    ]
}