# Kerbal Atomics

A mod pack for Kerbal Space Program, focused on delivering additional high quality nuclear thermal engine parts.

* [Features](#features)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Optional Patches](#optional-patches)
* [External Compatibility](#features)
* [Contributing](#contributing)

## Features

This mod features several new nuclear thermal engines that expand the range of nuclear propulsion options available. All these engines use a new resource, Liquid Hydrogen. Engines are provided in almost all size classes  

* **Bimodal Engines:** Can switch to using both LH2 and Oxidizer for a thrust boost at the cost of efficiency. Available in a 1.25m size.
* **Trimodal Engines:** Like a bimodal engine, but also generates a nice amount of energy when idle. In 0.625m, 1.25m and 2.5m sizes.
* **Gas Core Engines:** Advanced nuclear designs in closed-cyle and open-cycle versions. The open-cycle engine is horrifically overpowered, but cannot be refueled.
* **Nuclear Aerospikes:** For launch operations, a solid core and a gas core aerospike. Compromises, much like the regular stock aerospike

In addition, my CryoTanks mod is also bundled to provide fuel handling for Liquid Hydrogen.

* **Fuel Switching:** A set of patches provide fuel-switching features for most basic LF and LF/O tanks
* **Orbital Fuel Tanks:** A set of fuel tanks specially designed to contain LH2

For more information, check out the [CryoTanks readme](https://github.com/ChrisAdderley/CryoTanks/blob/master/README.md).

## Dependencies

### Required
These components are required for the mod to function and are bundled as part of any download:
* [ModuleManager (4.0.2)](https://github.com/sarbian/ModuleManager)
* [B9PartSwitch (2.6.0)](https://github.com/blowfishpro/B9PartSwitch)
* [Community Resource Pack (1.0.0)](https://github.com/BobPalmer/CommunityResourcePack)
* [CryoTanks (1.1.2)](https://github.com/ChrisAdderley/CryoTanks)
* [DynamicBatteryStorage (1.4.2)](https://github.com/ChrisAdderley/DynamicBatteryStorage)
* [DeployableEngines (1.0.1)](https://github.com/ChrisAdderley/DeployableEngines)

## Installation

To install, place the GameData folder inside your Kerbal Space Program folder. If asked to overwrite files, please do so.

NOTE: Do NOT rename or move folders within the GameData folder - this mod uses absolute paths to assets and will break if this happens.

## Optional Patches

Some extra patches are bundled that you can use to tweak your installation. To install them, drop the correct folder from the **Extras** folder into your KSP GameData Folder

* **KerbalAtomicsNTRModSupport**: Supports other NTR mods by converting their NTRs to use LiquidHydrogen
* **KerbalAtomicsNTRsUseLF**: Converts engines to use LF instead of LH2 at the cost of a big chunk of Isp
* **NearFutureElectricalNTRs**: When installed with [Near Future Electrical](https://github.com/ChrisAdderley/DeployableEngines), unlocks new functionality for nuclear engine operation. See more below

### Near Future Electrical Integration

For those desiring more integration with NF Electrical, such as power-producing reactors, the NearFutureElectricalNTRs patch can be installed. This increases reactor realism but also makes them much more complex to operate.

* **Reactor Integration**: NTRs have a reactor that must be activated and heated up before they can be used for thrust. Operating the engine without it on will produce no thrust and just waste propellant.
* **Reactor Cooling**: Like NFE power reactors, the NTR reactor has to be cooled while in use. Running propellant through the engine will remove 100% of generated heat, but if you want to leave the reactor on when not thrusting, you will need to add radiators.
* **Power Generation**: Trimodal NTRs can dedicate a bit of their capacity to produce power. The reactor must be on to do this, 1% reactor throttle is enough to generate full power/
* **Fuel Consumption**: Running the reactor will use up fuel, included in the engines. The engines can be refueled in the same was as the ones in NFE. Note that in this mode, the Emancipator engine can indeed be refueled.
* **Engine Heat Generation**: When this patch is installed, the "overheat" of the NTRs is disabled

## External Mod Compatibility

This mod includes compatibility patches for the following mods:
* [KSP-AVC](https://github.com/CYBUTEK/KSPAddonVersionChecker): Provides version checking
* [Community Tech Tree](https://github.com/ChrisAdderley/CommunityTechTree): Provides an expanded, community-sourced technology tree for modders to use

## Contributing

I certainly accept pull requests. Please target all such things to the `dev` branch though!

## Translations

For translation instructions please see [Localization Instructions](https://github.com/ChrisAdderley/KerbalAtomics/blob/master/GameData/KerbalAtomics/Localization/Localization.md)

* **Spanish:** KSP forum user fitiales
* **Russian:** KSP forum user prcreeper
* **German:** KSP forum user Three_Pounds

## Licensing


The art assets in this pack (all .dds, .png and .mu files) are distributed under an All Rights Reserved license. You may not redistribute or re-use these assets without express permission from the author.

Any bundled mods are distributed under their own licenses:
* ModuleManager by ialdabaoth and sarbian is distributed under a Creative Commons Sharealike license. More details, including source code, can be found [here](http://forum.kerbalspaceprogram.com/threads/31342-0-20-ModuleManager-1-3-for-all-your-stock-modding-needs?p=528607&viewfull=1#post528607)
* The Community Resource Pack by RoverDude is also distributed under its own license. Please find source and more details [here](https://github.com/BobPalmer/CommunityResourcePack)
* B9PartSwitch by blowfish is also distributed under its own license. Please find source and more details [here](https://github.com/blowfishpro/B9PartSwitch)

Everything else is distributed under the MIT license.

Copyright (c) 2019 Chris Adderley
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
