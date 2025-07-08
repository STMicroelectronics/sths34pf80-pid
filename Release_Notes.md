---
pagetitle: Release Notes for STHS34PF80 Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for STHS34PF80 Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the STHS34PF80 component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 20-June-2023</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.0.1 / 20-Oct-2023</label>
<div>

## Main changes

- Fix procedure to change odr in a safe way

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.0 / 07-Nov-2023</label>
<div>

## Main changes

- Redefine API name scheme removing "TMOS"

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V3.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Fix sths34pf80_safe_power_down never reaching drdy == 1.
- Fix potential endless recursion
- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V3.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V3.1.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>
:::

:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on STHS34PF80,
visit:
[STHS34PF80](https://www.st.com/resource/en/datasheet/sths34pf80.pdf)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
