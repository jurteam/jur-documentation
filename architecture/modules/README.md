# Modules

Jur modules are designed to be simple and evolve rapidly over time. Our runtime includes a set of modules that offers custom functionality to dApps and parachains.

The first priority is to offer these interfaces through our own dApps in order to demonstrate use cases of the Network State stack and eventually make it easy for anyone to build on top of this infrastructure.

The goal of each module is to be autonomous and independent so that the client, whether it is a parachain or an end user, can use it directly without relying on the other components. In some cases, a tradeoff was made to make the implementation simpler for now and those pallets will be re-engineered to be more flexible in the future as we accumulate learnings from actual usage and not our own assumptions.

We have followed the KISS principle in most of our implementation decisions.
