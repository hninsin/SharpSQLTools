

```
>SharpSQLTools.exe

   _____ _                      _____  ____  _   _______          _
  / ____| |                    / ____|/ __ \| | |__   __|        | |
 | (___ | |__   __ _ _ __ _ __| (___ | |  | | |    | | ___   ___ | |___
  \___ \| '_ \ / _` | '__| '_ \\___ \| |  | | |    | |/ _ \ / _ \| / __|
  ____) | | | | (_| | |  | |_) |___) | |__| | |____| | (_) | (_) | \__ \
 |_____/|_| |_|\__,_|_|  | .__/_____/ \___\_\______|_|\___/ \___/|_|___/
                         | |
                         |_|
                                                    by Rcoil & Uknow

Usage:

SharpSQLTools target username password                   - interactive console
SharpSQLTools target username password module command    - non-interactive console

Module:

enable_xp_cmdshell         - you know what it means
disable_xp_cmdshell        - you know what it means
xp_cmdshell {cmd}          - executes cmd using xp_cmdshell
enable_ole                 - you know what it means
disable_ole                - you know what it means
upload {local} {remote}    - upload a local file to a remote path (OLE required)
download {remote} {local}  - download a remote file to a local path
enable_clr                 - you know what it means
disable_clr                - you know what it means
install_clr                - create assembly and procedure
uninstall_clr              - drop clr
clr_dumplsass              - dumplsass by clr
clr_adduser {user} {pass}  - add user by clr
clr_download {url} {path}  - download file from url by clr
exit                       - terminates the server process (and this session)

```
