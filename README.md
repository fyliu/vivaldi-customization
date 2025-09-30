# Vivaldi Customizations

## How to use

- [Modding Vivaldi](https://forum.vivaldi.net/topic/10549/modding-vivaldi)

### Installing CSS mods

1. Open `vivaldi://flags`.
1. Enable "Allow for using CSS modifications".
1. Open Settings > Appearance.
1. Under "Custom UI Modifications", choose the folder containing your CSS files.
1. Place your CSS files in the folder.
1. Restart Vivaldi to apply the changes.

Note: Make sure the files have extension `.css`.
Note: Avoid having spaces in the file names and path.

### Installing JS mods

1. Open `vivaldi:about` in Vivaldi.
1. Note the Executable Path and extract the path
1. We're going to open up `window.html` inside [Executable Path]/resources/vivaldi/

### Inpecting Browser UI code

1. Open `vivaldi:inspect/#apps` in Vivaldi.
1. Click "inspect" on the Vivaldi app with the most tabs. That's the main window.

## Vertical Tabs

This is a css file that is loaded into the browser to customize tab bar behavior. It's based on the [Vertical Tabs mod](https://forum.vivaldi.net/topic/82900/vertical-tabs-collapsed-expand-on-hover) behavior.

### files

- `custom-css/vertical-extensions-dropdown.css`
- `custom-css/vertical-tabs.css`

### Behavior

- Auto expand and collapse tab bars on hover
- Tab bars expansions hover above the web page

### Requirements

- Tab bar must be vertical
- Nested tab bars should be set
- 2nd tab level should be locked
