(This is a fork. See up top.)

Downloads a torrent from what.cd to your `~/Downloads` directory.

##1. Add your username and password to config##

in `~/.config/whatcdsearch`:

    username: your_whatcd_username
    password: your_whatcd_password

##2a. Then use the provided shell script:##

    whatget "Radiohead" "In Rainbows"

##2b. Or not...##

    whatcdsearch -a "Talking Heads" -l "Live USA" -u jeff -p password

Arguments:

    --artist,   -a <s>:   Artist name
    --album,    -l <s>:   Album name
    --username, -u <s>:   What.CD username
    --password, -p <s>:   What.CD password
    --help,     -h:       Show this message
