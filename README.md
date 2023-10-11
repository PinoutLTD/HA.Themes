# Home Assistant theme
Home Assistant theme in Pinout colors

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
