tideways docker compose
=======================

Addon for your docker compose environment to support tideways APM and profiling
for your PHP applicaitons.

Environment variables
=====================

To allow Tideways usage you will have to add the following environment
variables to your `.env` file:

- TIDEWAYS_APIKEY
- TIDEWAYS_SAMPLERATE (optional, default set to 30)
- TIDEWAYS_COLLECT (optionals, default set to full)

The API key can be found in the settings of your configured application in the [Tideways app](https://app.tideways.io)
The other environment variables can be found in the [Tideways documentation](https://tideways.io/profiler/docs)

License
-------

MIT License (MIT). See [License File](LICENSE.md) for more information.
