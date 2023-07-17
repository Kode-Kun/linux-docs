### Polybar utils v0.1
- [Polybar config (official github example)](https://github.com/polybar/polybar/blob/master/doc/config.ini)
- Bar color for (gondola water): background:#DD3b465f background-alt:#526185
- Underline color (gondola water): primary:#a58355
- launch.sh (for AwesomeWM autostart, check AWESOME.md):
```bash
#!/bin/bash

killall -q polybar
while pgrep -u $UID -x polybar >/dev/null; do sleep 1; done
polybar kode &
```

