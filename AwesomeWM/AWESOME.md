### AwesomeWM utils v0.5
- [AwesomeWM ricing tutorial (outdated)](https://youtu.be/JONiwmvi3q0)
- Make windows' corners rounded:  
```lua
client.connect_signal("manage"), function (c)
	c.shape = gears.shape.rounded_rect
```
(add the **c.shape** line in the **client.connect** function(around line 495))
- Add processes to autostart in rc.lua:
```lua
awful.spawn.with_shell("/home/kode/.config/polybar/launch.sh")
```
- [AwesomeWM x polybar implementation tutorial(8:12 for rc.lua config)](https://youtu.be/ibRa4A4pIws)
- Add dmenu shortcut to rc.lua:
```lua
awful.key({ modkey },            "r",     function () awful.util.spawn_with_shell("dmenu_run") end))
```

