Icinga Web 2 Fileshipper module
===============================

The main purpose of this module is to extend [Icinga Director](https://github.com/icinga/icingaweb2-module-director)
using some of it's exported hooks. Based on them it offers an `Import Source`
able to deal with `CSV`, `JSON`, `YAML` and `XML` files. It also offers the
possibility to deploy hand-crafted [Icinga 2](https://github.com/Icinga/icinga2)
config files through the `Icinga Director`.

![Icinga Web 2 Fileshipper](doc/screenshot/fileshipper/01_fileshipper-imports-overview.png)

For getting started please read our [Installation instructions](doc/02-Installation.md),
and then you should be ready to dive into [Import Source](doc/03-ImportSource.md)
definitions, [supported file formats](doc/11-FileFormats.md) or and hand-crafted
[Config File Shipping](doc/04-FileShipping.md).

Changes
-------

### v1.2.0

* FEATURE: PHP 8 support
* FEATURE: Give guidance on potential misconfiguration (#34)
* FEATURE: do not fail on malformed config file (#35)

### v1.1.0

* FEATURE: Added XLSX file support

### v1.0.1

* FEATURE: CSV files should give NULL for columns with empty strings (#6)
* FIX: Small documentation fix
