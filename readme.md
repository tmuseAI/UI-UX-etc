# Notification System

## HOW TO USE

```lua
local NotifySystem = loadstring(game:HttpGet("YOUR_RAW_LINK_HERE"))()

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

-- Error (đỏ)
NotifySystem.Notify("", "", 5, "error")
```
