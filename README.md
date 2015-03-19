# Notify Send IMPROVED!
Acts exactly like notify-send, but with capabilities to replace or close old notifications.

Requires Python.

    Usage:
      notify-send [OPTION...] <SUMMARY> [BODY] - create a notification
      prints ID of created notification.

    Help Options:
      -?, --help                        Show help options

    Application Options:
      -u, --urgency=LEVEL               Specifies the urgency level (low, normal, critical).
      -t, --expire-time=TIME            Specifies the timeout in milliseconds at which to expire the notification.
      -a, --app-name=APP_NAME           Specifies the app name for the icon
      -i, --icon=ICON[,ICON...]         Specifies an icon filename or stock icon to display.
      -c, --category=TYPE[,TYPE...]     Specifies the notification category.
      -h, --hint=TYPE:NAME:VALUE        Specifies basic extra data to pass. Valid types are int, double, string and byte.
      -v, --version                     Version of the package.
      -r, --replace                     Replaces old notification posessing the specified id.
      -d, --close                       Closes notification with specified id.


