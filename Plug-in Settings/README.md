# Plug-in Settings

This contains all the plug-in presets I use in Logic Pro.

Note that some presets are for external plug-ins, which will need downloading.

Plug-in settings are stored as <samp>.pst</samp> files.

## Using Presets

A preset is a copy of all the parameters (excluding Sidechain) of a plug-in.

All presets are stored as <samp>.pst</samp> files.

### Downloading Presets

Download the entire folder containing presets.

For example, if you were interested in the [<samp>Channel EQ</samp>](/Plug-in%20Settings/Channel%20EQ/) presets,
download the entire

##

### Default Preset

The plug-in is inserted with the default preset.

The default preset can be set, modified, or deleted.

Be default, the default preset is the [<samp>Factory Preset</samp>].

#### User Default

The "User Default" preset is automatically set on plug-in insertion.

When active, the preset name will show up as <samp>User Default</samp>.

##### Defining a Default Preset

You can define custom default presets using two methods:

1. Save as Default
   Click the <samp>Save as Default</samp> button to save as the default preset.
2. Custom Name
   You could manually save a preset as the default by naming it <samp>#default</samp>
   (This is used internally to store the default).

##### Loading the Default Preset

Either:
- Insert the plug-in.
  The plug-in will be automatically initialised with the Default Preset.

Or:
- Open the plug-in.
  Click the plug-in preset name.
  This will open a drop-down menu.
  Click the <samp><kbd>Recall Default</kbd></samp> option.

When the default preset is loaded, the plug-in name will either be:
- [<samp>User Default</samp>] (if the [<samp>User Default</samp>] preset __is__ defined), or
- [<samp>Default Preset</samp>] (if the [<samp>User Default</samp>] preset is __not__ defined.

> [!tip]
> This method is can be used to re-obtain the [<samp>Factory Default</samp>] preset after
> the [<samp>User Default</samp>] preset is defined.
>
> See [Obtaining the](#obtaining-the-factory-default-preset)&nbsp;[<samp>Factory Default</samp>]&nbsp;[Preset](#obtaining-the-factory-default-preset).

##### Clearing the Default Preset

1. [Load the default](#loading-the-default-preset) preset.
2. Click the plug-in preset name.
   This will open a drop-down menu showing a list of presets.
3. Click <samp><kbd>Delete</kbd></samp>

#### Factory Default

The [<samp>Factory Default</samp>] preset is labelled "<samp>Default Preset.pst</samp>"

> [!note]
> The [<samp>Factory Default</samp>] is not included, it has been added manually.

> [!tip]
> ##### Obtaining the [<samp>Factory Default</samp>] Preset
>
> If you haven't yet defined a [<samp>User Default</samp>]
> setting, then the [<samp>Factory Default</samp>] is automatically applied on insertion.
>
> This happens even if the user has defined other presets.
>
> Else:
>
> 1. Load the [<samp>User Default</samp>] preset.

<!-- Links -->
[<samp>User Default</samp>]: #user-default
[<samp>Factory Default</samp>]: #factory-default
[<samp>Default Preset</samp>]: #default-preset
