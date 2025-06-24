# SCE JSON Sample Library

Welcome to the JSON sample library for the Sherman Calculation Engine (SCE). This
repository was created to assist developers get started coding their
applications by illustrating a variety of loans and features available with the
SCE.

If you are looking for complete documentation on the JSON interface to the SCE,
please see our [SCEJSON Reference
Manual](https://github.com/shermanloan/scejson-doc).

## Directories

Each directory corresponds to a single module made available by the SCE JSON
interface.

For closed end loan calculations, we recommend the use of the [Loan](Loan/) module,
unless you are quoting a construction loan without a permanent loan attached, in
which case the [Construction](Construction/) module is recommended.

Other compliance related modules for real-estate lending include the
[HOEPA/HCM](Hcm/) and [HPML](Hpml/) modules. We also offer a complete Regulation
Z [APR](Apr/) calculation and verification module.

For savings related calculations, we provide modules for [single deposit](Cd/),
[multiple deposit](Ira/), [annuity](Annuity/), and [APY](Apy/) calculations.
