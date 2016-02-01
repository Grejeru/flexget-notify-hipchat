# flexget-notify-hipchat
Hipchat notification plugin for Flexget

Example:
```yaml
      hipchat:
        auth:
          auth_token: <AUTH_TOKEN>
          room_key: <ROOM_KEY>
        [color: green|yellow|red|grey|purple (default: green)]
        [notify: true|false (default: false)]
        [title: <TITLE> (default: "New download started:")]
        [message: <MESSAGE_BODY> (default: "{{ series_name }} {{ series_id }} {{ quality }}" -- accepts Jinja2)]
        [url: <HIPCHAT_URL> (default: https://api.hipchat.com)]
```
Configuration parameters are also supported from entries (eg. through set).
