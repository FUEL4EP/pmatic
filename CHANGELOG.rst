The pmatic Changelog
====================

Unreleased (Use snapshot builds to get these changes)
-----------------------------------------------------

* HM-CC-RT-DN: Fixed low battery detection via ``device.is_battery_low``
* HM-CC-RT-DN: Added specific attributes/methods: ``device.temperature``,
  ``device.set_temperature``, ``device.is_off``, ``device.turn_off()``,
  ``device.control_mode``, ``device.battery_state``
* HM-PBI-4-FM: Changed access to switches from ``device.button(0)`` to
  a hopefully clearer ``device.switch1``, ``device.switch2``, ...

Version 0.1 (2016-03-13)
------------------------

* Initial testing release.