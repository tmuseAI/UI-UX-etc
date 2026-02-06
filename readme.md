# Notification System

## HOW TO USE

```lua
local NotifySystem = loadstring(game:HttpGet("https://raw.githubusercontent.com/tmuseAI/UI-UX-etc/refs/heads/main/noti.lua"))()

NotifySystem.Notify("Title", "Message", duration, "type")
```

## Ví dụ

```lua
-- Info (blue)
NotifySystem.Notify("", "", 3, "info")

-- Success (green)
NotifySystem.Notify("", "", 5, "success")

-- Warning (yellow)
NotifySystem.Notify("", "", 4, "warning")

-- Error (red)
NotifySystem.Notify("", "", 5, "error")
```
