[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [\<internal\>](../modules/internal_.md) / LicenseInformationFree

# Interface: LicenseInformationFree

[\<internal\>](../modules/internal_.md).LicenseInformationFree

## Table of contents

### Properties

- [license](internal_.LicenseInformationFree.md#license)
- [link](internal_.LicenseInformationFree.md#link)
- [type](internal_.LicenseInformationFree.md#type)

## Properties

### license

• `Optional` **license**: `string`

License of the software

#### Defined in

[types-dev/objects.d.ts:513](https://github.com/ioBroker/ioBroker.js-controller/blob/04f0eac95/packages/types-dev/objects.d.ts#L513)

___

### link

• `Optional` **link**: `string`

Hyperlink, where information about the license can be found. For non-free licenses the linked page should contain information about free features (if applicable), time of validity, link to shop and seller information.
This is required if the license type is different from 'free'. For 'free' licenses an optional link to the license file can be placed here.

#### Defined in

[types-dev/objects.d.ts:520](https://github.com/ioBroker/ioBroker.js-controller/blob/04f0eac95/packages/types-dev/objects.d.ts#L520)

___

### type

• **type**: ``"free"``

Use 'paid' for adapters which do not work without a paid license. Use 'commercial' for adapters which require a license for commercial use only. Use 'limited' if some functionalities are not available without a paid license.

#### Defined in

[types-dev/objects.d.ts:515](https://github.com/ioBroker/ioBroker.js-controller/blob/04f0eac95/packages/types-dev/objects.d.ts#L515)
