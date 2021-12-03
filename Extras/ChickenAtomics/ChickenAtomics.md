Chicken Gas Nuclear Thermal Rockets
=========

This patchset allows using liquid ammonia in NTRs. Dennis Nikitaev predicts
that ammonia propellant would result in 2x more thrust at 41% Isp. KSP-IE uses
1.4x thrust and 63% Isp. As a compromise, this patchset uses 1.7-1.8x thrust
and 60% Isp.

All multimode ntrs featuring LH2/LF switching are converted to LH2/NH3. Some
LA-NTRs are stripped of their oxidizer augmented mode and given NH3 modes
instead. And the Deliverance lightbulb rocket has been extended with ammonia
mode. The two later patches can be easily extended to other engines if desired.

Lastly, Ammonia configuration has been added to procedural liquid tank.

Due to incompatibility of ModuleSystemHeatFissionEngine with B9 based fuel
switching, more than two modes can't be added and in-flight switching can't be
disabled.

Requires: CRP, CryoTanks.

Recommends: Procedural Parts, Rational Resources.

Supports: SMURFF.
