# Change Log

All notable changes to this project will be documented in this file.

## Unreleased as of Sprint 65 ending 2017-07-24

### Added
- Parser methods for RbVmomi Inventory Collector [(#74)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/74)
- Rbvmomi inventory collector [(#72)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/72)
- Add VMware inventory collections [(#71)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/71)
- Decrypt and validate credentials in raw_connect  [(#69)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/69)

### Fixed
- Fix the VM Provisioning issue with auto replacement in selected dvPortGroup network. [(#78)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/78)

## Unreleased as of Sprint 63 ending 2017-06-19

### Fixed
- Vm restart guest check fixed [(#64)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/64)

## Unreleased as of Sprint 61 ending 2017-05-22

### Added
- Lookup SCSI Controller Device Type from Hardware  [(#51)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/51)

## Unreleased as of Sprint 60 ending 2017-05-08

### Fixed
- Decode slashes in more VMware inventory type names [(#53)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/53)

## Fine-1

### Added
- Allow folder as refresh target [(#32)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/32)
- Add a simple event history script [(#21)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/21)
- Add support for WebMKS remote consoles accessible from the UI [(#13)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/13)
- Add vm_acquire_ticket for webmks console types [(#9)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/9)
- Implements OrchestrationTemplate#deployment_options [(#8)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/8)

### Changed
- Removed supports_snapshots? methods defined independently without using supportsFeatureMixin plugin [(#14)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/14)

### Fixed
- Queue initial refresh if the Broker is available [(#41)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/41)
- Changes sysprep field to be a hash [(#35)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/35)
- Comment out GlobalVars to prevent it from breaking the rubocop config [(#38)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/38)
- Skip clusters with invalid configuration [(#36)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/36)
- Don't allow memory snapshot for powered off vms [(#30)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/30)
- Handle all DVPortGroups in the VMware Provision Workflow [(#25)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/25)
- Validate deviceMode on a VirtualDisk Backing before reconfigure [(#24)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/24)
- Allow changing the device type of an existing vnic [(#10)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/10)
- Fix issue provisioning to a VM Network from a DVS [(#11)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/11)
- Use the dvportgroup config.key for the uid_ems [(#5)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/5)
- Fix wrong number of arguments error when opening MKS console [(#15)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/15)
- Decode the dvSwitch and dvPortgroup name [(#4)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/4)
- Fix issue where EmsEvent.add_vc and add_vmware_vcloud methods no longer exists [(#7)](https://github.com/ManageIQ/manageiq-providers-vmware/pull/7)
