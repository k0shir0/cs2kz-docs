# Command help

Type `!help` or `/help` in chat to open or close the command reference. Select a category to see its commands, aliases, and descriptions. For example, `!help measure` opens the measurement category directly when help is closed.

The help window uses your selected language, with English fallback for untranslated text. It also uses your menu font, color, and sound preferences.

Command rows are read-only. Type a listed command in chat to use it. Scroll through the commands in the selected category. Close the window with `!help`, `/help`, or the button in its upper-right corner to return to normal movement.

Help has its own window. Opening `!options` closes help and opens the options menu; opening help closes options. Starting HUD editing closes help.

## Console help

Use `kz_help` in the console to list all command categories, or provide one or more category names:

```text
kz_help measure
kz_help checkpoint misc
```

If the help window is unavailable or you are editing the HUD, chat help prints the command reference to the console instead.
