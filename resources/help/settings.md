# Settings

There are an increasing number of settings that can be controlled in blightmud.
Settings are stored in `$CONFIGDIR/settings.ron` and can be either edited by
hand or toggled using `/set`. Changing some settings require a restart.

Settings are toggled as follows:

- `/set <setting>`           Shows a settings and its current value
- `/set <setting> on/off`    Toggles a setting on or off
- `/settings`                Show current value of all settings

Available settings are:

- `logging_enabled`     See `/help logging`
- `mouse_enabled`       Experimental mouse scrolling support. Requires restart.
- `save_history`        Save your last 100 commands to disk.
- `confirm_quit`        Ask for confirmation before quitting Blightmud when pressing `ctrl-c`.
- `scroll_split`        Split screen when scrolling
- `scroll_lock`         Set scroll position at start of text when showing long help files
- `tts_enabled`         Enable tts (only if compiled with TTS)
- `reader_mode`         Switches to a screen reader friendly TUI. (Does not support `status area`.)
