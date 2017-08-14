# ArkFrame

## A framework mod for quality of life features and for supporting intercommunication between ARK mods

---

The current state of planned design is that mod developers will download the ArkFrame source and make it available in the devkit as a secondary resource. Mod developers can base their blueprints off of the new class blueprints provided by ArkFrame, thus giving all participating mods a set of standardized methods aimed at intermod communication. The mod information is also registered with the ArkFrame negotiator object which gives oversight to providing information of one mod to another even without the source.

The system is currently in the early stages of development.

Current Planned Features:

* Runtime event logging (Log entires must be implemented by a mod developer for them to show up here) that will provide better insight into the interactions between mods and allow for easier debuging in the live environment.
* Resource dictionary functionality, support for standardizing resources of the same intended type (e.g. A copper resource in one mod will work for another even if it implemented its own item)
* Item generator subscription, mod authors will be able to subscribe desired items to various item generator type objects such as harvest components and supply drops. This will allow for greater stackability between mods that were previously unstackable.
* Inventory additions subscription to easily add additional items and blueprints to existing structures.
* Custom function call interface, a means for a mod to allow other mods to call functions that are otherwise innaccesable without source.
* Logic Expansions for existing classes.
* Mod information viewer.
* Mod Config Management.
* Remappable keybindings for mods.