Downloads a torrent (V0 if available) from what.cd to your `~/Downloads` directory.



####Setup####

1. Install ruby gems `trollop` and `mechanize`.

2. Create `~/.config/whatcdsearch`:
```
    username: your_whatcd_username
    password: your_whatcd_password
```

####Usage (shell script)####

    whatget "Radiohead" "In Rainbows"

####Usage (original)####

    whatcdsearch -a "Talking Heads" -l "Live USA" -u jeff -p password

Arguments:

    --artist,   -a <s>:   Artist name
    --album,    -l <s>:   Album name
    --username, -u <s>:   What.CD username
    --password, -p <s>:   What.CD password
    --help,     -h:       Show this message
