Sugar Bub Adapters
==================

.. contents::

Base Adapter
------------

The base adapter can be inserted into a Game Boy, and adapts the Game Boy cartridge interface to a FPC connector with the same pinout as the `Analogue AP-A01`_ Sega Game Gear adapter. This FPC connector can be connected directly to a `RetroSix GameSlot`_ or the Sugar Bub `SMS Adapter`_.

By harvesting the components from an AP-A01, the adapter can be made compatible with the Analogue Pocket. However, without harvesting the MCU_ or reverse-engineering its communication protocol, the Pocket will not recognize the adapter.

.. _Analogue AP-A01: https://github.com/sfiera/pocket-adapters/blob/main/gg.md
.. _RetroSix GameSlot: https://retrosix.co.uk/Game-Gear-GameSlot-Kit-p515558760
.. _MCU: https://github.com/sfiera/pocket-adapters/blob/main/mcu.md

PCB requirements:

* ENIG or hard gold finish (not HASL)
* 0.8mm thickness

Components:

* Amphenol F32Q-1A7H1-11045 FPC connector (45p, 0.5mm pitch)
* FPC cable (45p, 0.5mm pitch)
* SOIC-16 HC139 demux
* (optional) components from Analogue AP-A01

SMS Adapter
-----------

In combination with the `base adapter`_, the SMS adapter serves as a `Master Gear Converter`_ without the need of an intermediate Game Gear slot.

.. _Master Gear Converter: https://segaretro.org/Master_Gear_Converter

PCB requirements:

* Any finish
* Any thickness

Components:

* Amphenol F32Q-1A7H1-11045 FPC connector
* EDAC 395-050-521-802 edge connector
