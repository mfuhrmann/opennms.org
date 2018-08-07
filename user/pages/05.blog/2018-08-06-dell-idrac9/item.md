---
title: iDRAC 9 Support
date: 21:58 2018-08-06
author: Marcel Fuhrmann
body_classes: header-lite fullwidth blogstyling
taxonomy:
    category: opennms
    tag: [ dell, idrac, monitors, datacollection]
---

For those who don't know iDRAC, it's a remote controller for administrational work on your server.
Furthermore it provides a big bunch of monitoring metrics which we can use for OpenNMS.
We don't want to explain iDRAC here in detail because Dell did that already on their website:
http://www.dell.com/learn/us/en/08/shared-content~data-sheets~en/documents~idrac-spec-sheet.pdf

So what do we have?

* A big bunch of metrics and graphs out of:
  * powerSupplyTable
  * voltageProbeTable
  * amperageProbeTable
  * powerUsageTable
  * coolingDeviceTable
  * temperatureProbeTable
  * processorDeviceTable
  * memoryDeviceTable
  * batteryDeviceTable
  * controllerTable
  * physicalDiskTable
  * virtualDiskTable
* Status monitors and detectors for:
  * Dell-System-Health
  * Dell-LCD
  * Dell-Storage
  * Dell-Power
  * Dell-Memory
  * Dell-Processor
  * Dell-PCI-Device
  * Dell-NIC
  * Dell-VirtualDisk
  * Dell-PhysicalDisk
  * Dell-Fan
* 141 SNMP trap defintions

Check out the config module on Github: https://github.com/opennms-config-modules/dell-idrac9
