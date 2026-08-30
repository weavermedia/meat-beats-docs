## Installing Meat Beats plugins

Meat Beats plugins are provided in the following formats:

- Mac 64bit AU/VST3 for macOS Intel 10.14+ and all Apple Silicon versions
- Windows 64bit VST3 for Windows 10/11+

### Installing on Mac

**Mac AU**

Copy `ThePlugin.component` and the `ThePlugin.instruments` folder to:

`Macintosh HD > Library > Audio > Plug-Ins > Components`

**Mac VST3**

Copy `ThePlugin.vst3` and the `ThePlugin.instruments` folder to:

`Macintosh HD > Library > Audio > Plug-Ins > VST3`

Which format you install on Mac depends which DAW you use:

- Logic and GarageBand only use AU
- Cubase, Bitwig, Studio One and Reason only use VST3
- Ableton Live, FL Studio and Reaper can use either, so pick one format
- Pro Tools (AAX) is not supported

### Installing on Windows

**Windows VST3**

Copy `ThePlugin.vst3` and the `ThePlugin.instruments` folder to:

`C:\Program Files\Common Files\VST3`

### Post-installation

Rescan your plugin folder in your DAW to use the new plugin.

Logic and GarageBand may require a computer restart to see the plugin.

### Troubleshooting

If you see "Cannot find any instruments" check that the `.instruments` folder is in the same folder as the plugin.

Last updated: 2026-07-12

© [meatbeats.com](https://meatbeats.com)
