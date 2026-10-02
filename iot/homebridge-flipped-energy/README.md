# Homebridge

[homebridge-flipped-energy](https://github.com/flipped-energy/homebridge-flipped-energy) exposes your tariff periods, optional wholesale-price signals and metered usage to Apple Home through Homebridge. The Eve app displays energy history.

Install `@flipped-energy/homebridge-flipped-energy` through Homebridge, create a [read-only developer token](https://flipped.energy/accounts/developer?tab=tokens), and enter it in the plugin configuration. Follow the [plugin installation guide](https://github.com/flipped-energy/homebridge-flipped-energy#readme) for pairing and settings.

Metered history arrives after the meter data is available. Power calculated from an energy interval is an interval average, not a live meter reading.
