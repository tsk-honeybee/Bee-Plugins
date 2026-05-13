# Bee Plugins

Public metadata endpoint for Bee Audio plug-in updates.

Bee Talker reads:

```text
https://raw.githubusercontent.com/tsk-honeybee/Bee-Plugins/main/BeeTalker/update.json
```

Increase `latest_version` in `BeeTalker/update.json` when a new build is released. The plug-in shows the update dialog once per version, then keeps showing the update button until the installed version catches up.
