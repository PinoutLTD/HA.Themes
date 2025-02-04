# Home Assistant theme
Home Assistant theme in Pinout colors

## Install

### Using HACS

1. Navigate to the HACS panel and click on the three dots located in the upper right corner. Then, select `Custom repositories`.

2. Paste the provided link into the `Repository` field, select `Theme` from the `Category` dropdown menu, and click the `ADD` button.
```
https://github.com/PinoutLTD/HA.Themes
```
3. Next, search for `Pinout Theme` in the HACS search bar. Once found, select it and hit the `Download` button.

### Manual
1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```
2. Clone the repository
```bash
git clone https://github.com/PinoutLTD/HA.Themes.git
```

3. Copy `themes/pinout.yaml` in your existing (or create it) `themes/` folder.

```bash
mv HA.Themes/themes/pinout.yaml <PATH_TO_YOUR_HOME_ASSISTANT_FOLDER>/themes/.
```
