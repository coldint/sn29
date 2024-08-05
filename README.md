# Subnet 29 dynamic configuration repository
This repository functions as a dynamic configuration source for subnet 29 validators.
It allows to inform all active validators in (near) real-time, without requiring an update
and restart. The validator code and installation instructions can be found in the
[coldint validator repo](https://github.com/coldint/coldint_validator).

This has several use-cases:
- Hall of Fame reward distribution
- Competition updates

## Hall of Fame configuration
The [Hall of Fame](hall_of_fame.json) is a core principle of Coldint SN29, and
allows to instruct validators to assign weight to hotkeys which have
contributed to the goals of this subnet, in the form of code, bug-fixes or key
insights.

## Competition updates
The aim of this subnet is to provide a dynamic playing field for AI R&D and
product development. To support this, new competitions will be started
regularly. In some cases this will require validator updates, in other cases
they can be added or modified by changing the [online configuration of competitions](competitions.json).
The weight distribution between the different competitions can be modified over
time, so that new experiments can start out small and get more emphasis if they
look promising.
Dynamic configuration allows to transition smoothly between different
competitions without having to continuously update and restart validators.
