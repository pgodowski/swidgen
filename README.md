# swidgen
A small stand-alone (no hosting required) Web application that generates [SWID](https://tagvault.org/swid-tags/) tags based on the provided user-input.
The SWID tags are the little XML marker files, describing the software applications, including basic identification details,
like application name & version, vendor name, etc. Sample generated tag below:


```xml
<?xml version="1.0" encoding="utf-8" ?>
<SoftwareIdentity xml:lang="EN" name="SWIDGen" version="1.0.0.0" 
 versionScheme="multipartnumeric" 
 tagId="swidgen-d6c7bb0e-592f-c04b-031c-445fb07749a2_1.0.0.0" 
 xmlns="http://standards.iso.org/iso/19770/-2/2015/schema.xsd"> 
 xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
 xsi:schemaLocation="http://standards.iso.org/iso/19770/-2/2015-current/schema.xsd schema.xsd" >
  <Meta generator="SWID Tag Online Generator v0.1" /> 
  <Entity name="pgodowski" regid="github.com/pgodowski" role="tagCreator" /> 
</SoftwareIdentity>
```


### Tag Conformance
The generated ISO 19770-2 SWID tag conforms to the [ISO 19770-2:2015](https://www.iso.org/standard/65666.html) schema.

#### Other similar tools
[TagVault.org's](https://tagvault.org/tools/swid-signing-tool/) tag generator & digital signing tool.
