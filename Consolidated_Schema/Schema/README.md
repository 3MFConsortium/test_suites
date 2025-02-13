The normative requirements for 3MF consist of a Core specification and several Extension specifications. The Core specification appendices include an XML schema. Each 3MF Extension specification has appendices that document the schema objects relevant to the extension and how they fit into the Core schema. However, a single consolidated schema covering the Core specification and all the related Extensions is not part of the formal 3MF standards documentation. 

As part of the 3MF test suite development, QualityLogic, Inc developed a consolidated 3MF schema so that test cases could be validated prior to delivering them the 3MF consortium. This required changes to the organization of various schema objects and several compromises were made when conflicts in optionality or restrictions existed across extension specifications.

This [3MF Consolidated Schema](qli_3MF.xsd) is being made available to the user community to simplify the task of validating 3MF package parts against the schema requirements. And to enable 3MF users to integrate their private namespace extensions into the consolidated schema to provide complete validation of the 3MF packages they generate. Please note that the Core and Extension specifications appendices remain the authoritative resource for the 3MF schema. 

The consolidated schema  utilized the requirements from the following 3MF specifications:
* [3MF Core Specification - Version 1.3.0](https://github.com/3MFConsortium/spec_core/blob/1.3.0/3MF%20Core%20Specification.md)
* [3MF Materials and Properties Extension - Version 1.2.1](https://github.com/3MFConsortium/spec_materials/blob/1.2.1/3MF%20Materials%20Extension.md)
* [3MF Production Extension - Version 1.2.0](https://github.com/3MFConsortium/spec_production/blob/1.1.2/3MF%20Production%20Extension.md)
* [3MF Slice Extension - Version 1.0.2](https://github.com/3MFConsortium/spec_slice/blob/1.0.2/3MF%20Slice%20Extension.md) 
* [3MF Beam Lattice Extension - Version 1.2.0](https://github.com/3MFConsortium/spec_beamlattice/blob/1.2.0/3MF%20Beam%20Lattice%20Extension.md) 
* [3MF Secure Content Extension - Version 1.0.2](https://github.com/3MFConsortium/spec_securecontent/blob/1.0.2/3MF%20Secure%20Content.md) 
* [Office Open XML File Formats - Open Packaging Conventions - December 2012](https://www.ecma-international.org/news/TC45_current_work/Office%20Open%20XML%20Part%202%20-%20Open%20Packaging%20Conventions.pdf)
* [3MF Boolean Operations Extension - Version 1.1.0](https://github.com/3MFConsortium/spec_booleans/blob/1.1.0/3MF%20Boolean%20operations.md) 
* [3MF Displacement Extension - Version 1.0.0](https://github.com/3MFConsortium/spec_displacement/blob/1.0.0/3MF%20Displacement%20Extension.md) 

It includes the draft versions of the following 3MF extensions:

* [3MF Volumetric Extension - Pre-release 0.8.0](https://github.com/3MFConsortium/spec_volumetric/blob/master/3MF%20Volumetric%20Extension.md) 
