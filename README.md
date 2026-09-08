# hacs-isy994 (mike2)

Custom Home Assistant integration for Universal Devices ISY/IoX, based on [shbatm/hacs-isy994](https://github.com/shbatm/hacs-isy994), with local **mike2** changes.

Library: [mjcumming/pyisyox](https://github.com/mjcumming/pyisyox) (`1.0.0b0-mike2`).

## Production install

Do **not** let HACS auto-update this from GitHub. HACS previously wiped the local copy when the GitHub repo 404'd.

1. Copy `custom_components/isy994` onto the HA host.
2. Vendor `pyisyox` at `/config/pyisyox`.
3. Keep `manifest.json` requirements as `pyisyox @ file:///config/pyisyox`.

After editing this repo, copy those two trees onto cabin and Queen.
