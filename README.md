Awesome WM configuration files
==============================

## Installation
* Copy files to `$XDG_CONFIG_HOME/awesome/` or `$HOME/.config/awesome/`
* Install dependencies
* Configure incron with `incrontab -e`

    /var/log/kern.log IN_MODIFY sh /etc/xdg/awesome/popLog.sh /var/log/kern.log
    /var/log/auth.log IN_MODIFY sh /etc/xdg/awesome/popLog.sh /var/log/auth.log
    /var/log/ufw.log IN_MODIFY sh /etc/xdg/awesome/popLog.sh /var/log/ufw.log

## Compatibility
* Awesome v3.5 (Last Christmas)
* http://awesome.naquadah.org/

## Dependencies
* source-highlight
* libnotify-bin
* incron (inotify cron daemon)

## References
* http://awesome.naquadah.org/wiki/Dbus,_naughty_and_logs
* http://awesome.naquadah.org/wiki/Vicious
* http://awesome.naquadah.org/wiki/Awesome_3.4_to_3.5
