# SI Snitch

SI Snitch is a debugging tool for reading claims passed to Sitecore from Sitecore Identity, after transformation of those claims from Sitecore Identity. It can be helpful in:

* Identifying claims that Sitecore is getting, and in what format
* Ensuring group transformations in Sitecore Identity are being processed properly

Since SI Snitch dumps all claims into the log file of the system, it's *highly recommended* that this only be used in development environments. Use at your own risk!

## Usage

* Build SI Snitch
* Deploy assembly to /bin
* Deploy configuration to App_Config/Environment
* View claims in log files.

## Support
The code, samples and/or solutions provided in this repository are unsupported by Sitecore. Don't even think of opening a support incident related to issues with this code.

## Warranty
The code, samples and/or solutions provided in this repository are for example purposes only and without warranty (expressed or implied). The code has not been extensively tested and is not guaranteed to be bug free.
