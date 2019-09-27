---
title: Normative Rules
icon: fa-list
description: This is a compiled list of normative rules from NIEM specifications, including the NDR and the MPD Specification.
links:
  - url: /reference/specifications/normative-rules/3.0/
---

This section contains a listing of the normative rules, for use as a quick reference guide for the following:

* [Conformance Targets Attribute Specification (CTAS)](#ctas)
* [Model Package Description (MPD) specification](#model-package)
* [Naming and Design Rules (NDR) specification](#ndr)
* [Code Lists Specification](#cl)

---

{% assign url = site.data.links.ctas %}

<h4 id="ctas" style="padding-top: 65px; margin-top: -65px;"><a href="{{ url }}">Conformance Targets Attribute Rules</a></h4>

The CTAS defines XML attributes that may occur within XML documents to establish a claim that the document conforms to a set of conformance targets. The CTAS does not define conformance targets; conformance targets are defined in the [MPD Section 3.1](http://reference.niem.gov/niem/specification/model-package-description/3.0/model-package-description-3.0.html#section_3.1) and [NDR Section 3.6](http://reference.niem.gov/niem/specification/naming-and-design-rules/3.0/NIEM-NDR-3.0-2014-07-31.html#definition_conformance_target). There are six CTAS rules.

* [Rule 3-1, *Conformant document is an XML document*]({{ url }}#rule_3-1)
* [Rule 3-2, *Attribute `ct:conformanceTargets` is valid*]({{ url }}#rule_3-2)
* [Rule 3-3, *Namespace defines only attribute `ct:conformanceTargets`*]({{ url }}#rule_3-3)
* [Rule 3-4, *No reference to types in conformance targets namespace*]({{ url }}#rule_3-4)
* [Rule 3-5, *Attribute `ct:conformanceTargets` contains only absolute IRI references*]({{ url }}#rule_3-5)
* [Rule 3-6, *Document may contain any number of `ct:conformanceTargets` attributes*]({{ url }}#rule_3-6)
{: class="list-unstyled"}

---

{% assign url = site.data.links.mpd_spec %}

<h4 id="model-package" style="padding-top: 65px; margin-top: -65px;"><a href="{{ url }}">Model Package Description Specification</a></h4>

The MPD specification contains 60 normative rules for constructing a:

* NIEM Information Exchange Package Documentation (IEPD),
* NIEM Release (including a micro, minor, or major)
* NIEM Domain Update
* NIEM Core Update to a NIEM release
* NIEM Enterprise Information Exchange Model (EIEM)
{: }

* [Rule 3-1, *MPD Conformance Target Identifier*]({{ url }}#rule_3-1)
* [Rule 3-2, *MPD with MPD class of IEPD is an IEPD*]({{ url }}#rule_3-2)
* [Rule 3-3, *IEPD Conformance Target Identifier*]({{ url }}#rule_3-3)
* [Rule 4-1, *Fundamental NIEM Subset Rule*]({{ url }}#rule_4-1)
* [Rule 5-1, *MPD Has an `mpd-catalog.xml` in its Root Directory*]({{ url }}#rule_5-1)
* [Rule 5-2, *MPD Catalog Document Valid to `mpd-catalog-3.0.xsd`*]({{ url }}#rule_5-2)
* [Rule 5-3, *MPD Catalog Extension XML Catalog Document in Root Directory*]({{ url }}#rule_5-3)
* [Rule 5-4, *MPD Catalog Extension XML Catalog Document Name Is `mpd-catalog-extension-xml-catalog.xml`*]({{ url }}#rule_5-4)
* [Rule 5-5, *MPD Catalog Extension XML Catalog Document Resolves Namespaces to URIs*]({{ url }}#rule_5-5)
* [Rule 5-6, *MPD Catalog Extension Schema Document Conforms to NDR Extension Rules*]({{ url }}#rule_5-6)
* [Rule 5-7, *MPD Catalog Schema and Its Extensions Conform to NDR Schema Set Rules*]({{ url }}#rule_5-7)
* [Rule 5-8, *MPD Schema Document Extension Support Schemas Are Supersets of Spec Subsets*]({{ url }}#rule_5-8)
* [Rule 5-9, *MPD Class Determined by Conformance Target Identifier in `c:mpdClassURIList`*]({{ url }}#rule_5-9)
* [Rule 5-10, *MPD Version Number Syntax*]({{ url }}#rule_5-10)
* [Rule 5-11, *MPD URI Is Absolute*]({{ url }}#rule_5-11)
* [Rule 5-12, *MPD URI Supports Fragment*]({{ url }}#rule_5-12)
* [Rule 5-13, *MPD URI Has No Fragment*]({{ url }}#rule_5-13)
* [Rule 5-14, *MPD Artifact URI Syntax*]({{ url }}#rule_5-14)
* [Rule 5-15, *`c:pathURI` Resolves to a Resource*]({{ url }}#rule_5-15)
* [Rule 5-16, *`c:pathURI` for `c:XMLCatalog`*]({{ url }}#rule_5-16)
* [Rule 5-17, *`c:pathURI` for `c:MPDChangeLog`*]({{ url }}#rule_5-17)
* [Rule 5-18, *`c:pathURI` for `c:ReadMe`*]({{ url }}#rule_5-18)
* [Rule 5-19, *`c:pathURI` for `c:IEPSampleXMLDocument`*]({{ url }}#rule_5-19)
* [Rule 5-20, *`c:pathURI` for `c:BusinessRulesArtifact`*]({{ url }}#rule_5-20)
* [Rule 5-21, *`c:pathURI` for `c:XMLSchemaDocument`*]({{ url }}#rule_5-21)
* [Rule 5-22, *`c:pathURI` for `c:ExternalSchemaDocument`*]({{ url }}#rule_5-22)
* [Rule 5-23, *`c:pathURI` for `c:ReferenceSchemaDocument`*]({{ url }}#rule_5-23)
* [Rule 5-24, *`c:pathURI` for `c:ExtensionSchemaDocument`*]({{ url }}#rule_5-24)
* [Rule 5-25, *`c:pathURI` for `c:SubsetSchemaDocument`*]({{ url }}#rule_5-25)
* [Rule 5-26, *`c:pathURI` for `c:Wantlist`*]({{ url }}#rule_5-26)
* [Rule 5-27, *`c:pathURI` for `c:SchematronSchema`*]({{ url }}#rule_5-27)
* [Rule 5-28, *`c:pathURI` for `c:RelaxNGSchema`*]({{ url }}#rule_5-28)
* [Rule 5-29, *`c:pathURI` for `c:SchemaDocumentSet`*]({{ url }}#rule_5-29)
* [Rule 5-30, *`c:pathURI` for `c:ConstraintSchemaDocumentSet`*]({{ url }}#rule_5-30)
* [Rule 5-31, `c:pathURI`]({{ url }}#rule_5-31)
* [Rule 5-32, *Resolve MPD URI with Fragment*]({{ url }}#rule_5-32)
* [Rule 5-33, *XML Catalog `uri` Value Resolves to Resource*]({{ url }}#rule_5-33)
* [Rule 5-34, *XML Catalog `uri` Value Resolves to Resource with Correct Target Namespace*]({{ url }}#rule_5-34)
* [Rule 5-35, *IEPD Has a Change Log*]({{ url }}#rule_5-35)
* [Rule 5-36, *Readme Describes Purpose, Scope, Business Value, etc.*]({{ url }}#rule_5-36)
* [Rule 5-37, *IEPD Has a ReadMe Artifact*]({{ url }}#rule_5-37)
* [Rule 5-38, *Conformance Target Identifier*]({{ url }}#rule_5-38)
* [Rule 5-39, *IEP Conformance Target Has a `structures:id`*]({{ url }}#rule_5-39)
* [Rule 5-40,]({{ url }}#rule_5-40) [*IEPD Declares One or More IEP Conformance Targets*]({{ url }}#definition_information_exchange_package_documentation)
* [Rule 5-41, validity constraint context]({{ url }}#rule_5-41)
* [Rule 5-42, *Identifying the Document Element of an IEP*]({{ url }}#rule_5-42)
* [Rule 5-43, *Validating an XPath Expression*]({{ url }}#rule_5-43)
* [Rule 5-44, *IEPD Has an IEP Sample for Each `c:IEPConformanceTarget`*]({{ url }}#rule_5-44)
* [Rule 5-45, *Validating an IEP Sample XML Document*]({{ url }}#rule_5-45)
* [Rule 5-46, *IEPD Has Conformance Assertion*]({{ url }}#rule_5-46)
* [Rule 6-1, *Wantlist Location*]({{ url }}#rule_6-1)
* [Rule 7-1, *MPD Is a ZIP File*]({{ url }}#rule_7-1)
* [Rule 7-2, *XSD and XML Documents Conform to Applicable NDR Conformance Targets*]({{ url }}#rule_7-2)
* [Rule 7-3, *MPD Archive Uncompresses to a Single Root Directory*]({{ url }}#rule_7-3)
* [Rule 7-4, *Constraint on Elements of Type `c:SchemaDocumentSetType`*]({{ url }}#rule_7-4)
* [Rule 7-5, *IEPD File Name Syntax*]({{ url }}#rule_7-5)
* [Rule 7-6, *MPD Reference to Resource Uses Common URI Scheme*]({{ url }}#rule_7-6)
* [Rule 7-7, *IEPD Completeness*]({{ url }}#rule_7-7)
* [Rule 7-8, *MPD External Schema Documents Are Local Resources*]({{ url }}#rule_7-8)
* [Rule 7-9, *Key MPD Resources Are Local Resources*]({{ url }}#rule_7-9)
{: class="list-unstyled"}

---

{% assign url = site.data.links.ndr %}

<h4 id="ndr" style="padding-top: 65px; margin-top: -65px;"><a href="{{ url }}">Naming and Design Rules</a></h4>

The NIEM v4.0 NDR contains 255 normative rules defined in six sections of the specification (i.e., Section 4, 7, 9, 10, 11, 12). NIEM NDR apply to four categories of conformance targets denoted at the end of each rule in parenthesis. The codes representing conformance targets are as follows:

| Conformance Target | Description |
| ------------------ | ----------- |
| REF | Reference schema document |
| EXT | Extension schema document |
| SET | Conformant schema document set |
| INS | Conformant instance XML document |
{:.table-auto}

What follows is a numerical listing of each NDR rule.

* [Rule 4-1, *Schema marked as reference schema document must conform* (SET)]({{ url }}#rule_4-1)
* [Rule 4-2, *Schema marked as extension schema document must conform* (SET)]({{ url }}#rule_4-2)
* [Rule 4-3, *Schema is CTAS-conformant* (REF, EXT)]({{ url }}#rule_4-3)
* [Rule 4-4, *Document element has attribute ct:conformanceTargets* (REF, EXT)]({{ url }}#rule_4-4)
* [Rule 4-5, *Schema claims reference schema conformance target* (REF)]({{ url }}#rule_4-5)
* [Rule 4-6, *Schema claims extension conformance target* (EXT)]({{ url }}#rule_4-6)
* [Rule 7-1, *Document is an XML document* (REF, EXT, INS)]({{ url }}#rule_7-1)
* [Rule 7-2, *Document uses XML namespaces properly* (REF, EXT, INS)]({{ url }}#rule_7-2)
* [Rule 7-3, *Document is a schema document* (REF, EXT)]({{ url }}#rule_7-3)
* [Rule 7-4, *Document element is xs:schema* (REF, EXT)]({{ url }}#rule_7-4)
* [Rule 7-5, *Component name follows ISO 11179 Part 5 Annex A* (REF, EXT)]({{ url }}#rule_7-5)
* [Rule 9-1, *No base type in the XML namespace* (REF, EXT)]({{ url }}#rule_9-1)
* [Rule 9-2, *No base type of xs:ID* (REF, EXT)]({{ url }}#rule_9-2)
* [Rule 9-3, *No base type of xs:IDREF* (REF, EXT)]({{ url }}#rule_9-3)
* [Rule 9-4, *No base type of xs:IDREFS* (REF, EXT)]({{ url }}#rule_9-4)
* [Rule 9-5, *No base type of xs:anyType* (REF, EXT)]({{ url }}#rule_9-5)
* [Rule 9-6, *No base type of xs:anySimpleType* (REF, EXT)]({{ url }}#rule_9-6)
* [Rule 9-7, *No base type of xs:NOTATION* (REF, EXT)]({{ url }}#rule_9-7)
* [Rule 9-8, *No base type of xs:ENTITY* (REF, EXT)]({{ url }}#rule_9-8)
* [Rule 9-9, *No base type of xs:ENTITIES* (REF, EXT)]({{ url }}#rule_9-9)
* [Rule 9-10, *Simple type definition is top-level* (REF, EXT)]({{ url }}#rule_9-10)
* [Rule 9-11, *No simple type disallowed derivation* (REF)]({{ url }}#rule_9-11)
* [Rule 9-12, *Simple type has data definition* (REF, EXT)]({{ url }}#rule_9-12)
* [Rule 9-13, *No use of fixed on simple type facets* (REF)]({{ url }}#rule_9-13)
* [Rule 9-14, *Enumeration has data definition* (REF, EXT)]({{ url }}#rule_9-14)
* [Rule 9-15, *No list item type of xs:ID* (REF, EXT)]({{ url }}#rule_9-15)
* [Rule 9-16, *No list item type of xs:IDREF* (REF, EXT)]({{ url }}#rule_9-16)
* [Rule 9-17, *No list item type of xs:anySimpleType* (REF, EXT)]({{ url }}#rule_9-17)
* [Rule 9-18, *No list item type of xs:ENTITY* (REF, EXT)]({{ url }}#rule_9-18)
* [Rule 9-19, *No union member types of xs:ID* (REF, EXT)]({{ url }}#rule_9-19)
* [Rule 9-20, *No union member types of xs:IDREF* (REF, EXT)]({{ url }}#rule_9-20)
* [Rule 9-21, *No union member types of xs:IDREFS* (REF, EXT)]({{ url }}#rule_9-21)
* [Rule 9-22, *No union member types of xs:anySimpleType* (REF, EXT)]({{ url }}#rule_9-22)
* [Rule 9-23, *No union member types of xs:ENTITY* (REF, EXT)]({{ url }}#rule_9-23)
* [Rule 9-24, *No union member types of xs:ENTITIES* (REF, EXT)]({{ url }}#rule_9-24)
* [Rule 9-25, *Complex type definition is top-level* (REF, EXT)]({{ url }}#rule_9-25)
* [Rule 9-26, *Complex type has data definition* (REF, EXT)]({{ url }}#rule_9-26)
* [Rule 9-27, *No mixed content on complex type* (REF, EXT)]({{ url }}#rule_9-27)
* [Rule 9-28, *No mixed content on complex content* (REF, EXT)]({{ url }}#rule_9-28)
* [Rule 9-29, *Complex type content is explicitly simple or complex* (REF, EXT)]({{ url }}#rule_9-29)
* [Rule 9-30, *Complex content uses extension* (REF)]({{ url }}#rule_9-30)
* [Rule 9-31, *Base type of complex type with complex content must have complex content* (REF, EXT)]({{ url }}#rule_9-31)
* [Rule 9-32, *Base type of complex type with complex content must have complex content* (SET)]({{ url }}#rule_9-32)
* [Rule 9-33, *Simple content uses extension* (REF)]({{ url }}#rule_9-33)
* [Rule 9-34, *No complex type disallowed substitutions* (REF)]({{ url }}#rule_9-34)
* [Rule 9-35, *No complex type disallowed derivation* (REF)]({{ url }}#rule_9-35)
* [Rule 9-36, *Element declaration is top-level* (REF, EXT)]({{ url }}#rule_9-36)
* [Rule 9-37, *Element declaration has data definition* (REF, EXT)]({{ url }}#rule_9-37)
* [Rule 9-38, *Untyped element is abstract* (REF, EXT)]({{ url }}#rule_9-38)
* [Rule 9-39, *Element of type xs:anySimpleType is abstract* (REF, EXT)]({{ url }}#rule_9-39)
* [Rule 9-40, *Element type not in the XML Schema namespace* (REF, EXT)]({{ url }}#rule_9-40)
* [Rule 9-41, *Element type not in the XML namespace* (REF, EXT)]({{ url }}#rule_9-41)
* [Rule 9-42, *Element type is not simple type* (REF, EXT)]({{ url }}#rule_9-42)
* [Rule 9-43, *No element disallowed substitutions* (REF)]({{ url }}#rule_9-43)
* [Rule 9-44, *No element disallowed derivation* (REF)]({{ url }}#rule_9-44)
* [Rule 9-45, *No element default value* (REF, EXT)]({{ url }}#rule_9-45)
* [Rule 9-46, *No element fixed value* (REF, EXT)]({{ url }}#rule_9-46)
* [Rule 9-47, *Element declaration is nillable* (REF)]({{ url }}#rule_9-47)
* [Rule 9-48, *Attribute declaration is top-level* (REF, EXT)]({{ url }}#rule_9-48)
* [Rule 9-49, *Attribute declaration has data definition* (REF, EXT)]({{ url }}#rule_9-49)
* [Rule 9-50, *Attribute declaration has type* (REF, EXT)]({{ url }}#rule_9-50)
* [Rule 9-51, *No attribute type of xs:ID* (REF, EXT)]({{ url }}#rule_9-51)
* [Rule 9-52, *No attribute type of xs:IDREF* (REF, EXT)]({{ url }}#rule_9-52)
* [Rule 9-53, *No attribute type of xs:IDREFS* (REF, EXT)]({{ url }}#rule_9-53)
* [Rule 9-54, *No attribute type of xs:ENTITY* (REF, EXT)]({{ url }}#rule_9-54)
* [Rule 9-55, *No attribute type of xs:ENTITIES* (REF, EXT)]({{ url }}#rule_9-55)
* [Rule 9-56, *No attribute type of xs:anySimpleType* (REF, EXT)]({{ url }}#rule_9-56)
* [Rule 9-57, *No attribute default values* (REF, EXT)]({{ url }}#rule_9-57)
* [Rule 9-58, *No fixed values for optional attributes* (REF, EXT)]({{ url }}#rule_9-58)
* [Rule 9-59, *No use of element xs:notation* (REF, EXT)]({{ url }}#rule_9-59)
* [Rule 9-60, *Model group does not affect meaning* (EXT)]({{ url }}#rule_9-60)
* [Rule 9-61, *No xs:all* (REF, EXT)]({{ url }}#rule_9-61)
* [Rule 9-62, *xs:sequence must be child of xs:extension* (REF)]({{ url }}#rule_9-62)
* [Rule 9-63, *xs:sequence must be child of xs:extension or xs:restriction* (EXT)]({{ url }}#rule_9-63)
* [Rule 9-64, *No xs:choice* (REF)]({{ url }}#rule_9-64)
* [Rule 9-65, *xs:choice must be child of xs:sequence* (EXT)]({{ url }}#rule_9-65)
* [Rule 9-66, *Sequence has minimum cardinality 1* (REF, EXT)]({{ url }}#rule_9-66)
* [Rule 9-67, *Sequence has maximum cardinality 1* (REF, EXT)]({{ url }}#rule_9-67)
* [Rule 9-68, *Choice has minimum cardinality 1* (EXT)]({{ url }}#rule_9-68)
* [Rule 9-69, *Choice has maximum cardinality 1* (EXT)]({{ url }}#rule_9-69)
* [Rule 9-70, *No use of xs:any* (REF)]({{ url }}#rule_9-70)
* [Rule 9-71, *No use of xs:anyAttribute* (REF)]({{ url }}#rule_9-71)
* [Rule 9-72, *No use of xs:unique* (REF, EXT)]({{ url }}#rule_9-72)
* [Rule 9-73, *No use of xs:key* (REF, EXT)]({{ url }}#rule_9-73)
* [Rule 9-74, *No use of xs:keyref* (REF, EXT)]({{ url }}#rule_9-74)
* [Rule 9-75, *No use of xs:group* (REF, EXT)]({{ url }}#rule_9-75)
* [Rule 9-76, *No definition of attribute groups* (REF, EXT)]({{ url }}#rule_9-76)
* [Rule 9-77, *Comment is not recommended* (REF, EXT)]({{ url }}#rule_9-77)
* [Rule 9-78, *Documentation element has no element children* (REF, EXT)]({{ url }}#rule_9-78)
* [Rule 9-79, *xs:appinfo children are comments, elements, or whitespace* (REF, EXT)]({{ url }}#rule_9-79)
* [Rule 9-80, *Appinfo child elements have namespaces* (REF, EXT)]({{ url }}#rule_9-80)
* [Rule 9-81, *Appinfo descendants are not XML Schema elements* (REF, EXT)]({{ url }}#rule_9-81)
* [Rule 9-82, *Schema has data definition* (REF, EXT)]({{ url }}#rule_9-82)
* [Rule 9-83, *Schema document defines target namespace* (REF, EXT)]({{ url }}#rule_9-83)
* [Rule 9-84, *Target namespace is absolute URI* (REF, EXT)]({{ url }}#rule_9-84)
* [Rule 9-85, *Schema has version* (REF, EXT)]({{ url }}#rule_9-85)
* [Rule 9-86, *No disallowed substitutions* (REF)]({{ url }}#rule_9-86)
* [Rule 9-87, *No disallowed derivations* (REF)]({{ url }}#rule_9-87)
* [Rule 9-88, *No use of xs:redefine* (REF, EXT)]({{ url }}#rule_9-88)
* [Rule 9-89, *No use of xs:include* (REF, EXT)]({{ url }}#rule_9-89)
* [Rule 9-90, *xs:import must have namespace* (REF, EXT)]({{ url }}#rule_9-90)
* [Rule 9-91, *XML Schema document set must be complete* (SET)]({{ url }}#rule_9-91)
* [Rule 9-92, *Namespace referenced by attribute type is imported* (REF, EXT)]({{ url }}#rule_9-92)
* [Rule 9-93, *Namespace referenced by attribute base is imported* (REF, EXT)]({{ url }}#rule_9-93)
* [Rule 9-94, *Namespace referenced by attribute itemType is imported* (REF, EXT)]({{ url }}#rule_9-94)
* [Rule 9-95, *Namespaces referenced by attribute memberTypes is imported* (REF, EXT)]({{ url }}#rule_9-95)
* [Rule 9-96, *Namespace referenced by attribute ref is imported* (REF, EXT)]({{ url }}#rule_9-96)
* [Rule 9-97, *Namespace referenced by attribute substitutionGroup is imported* (REF, EXT)]({{ url }}#rule_9-97)
* [Rule 10-1, *Complex type has a category* (REF, EXT)]({{ url }}#rule_10-1)
* [Rule 10-2, *Object type with complex content is derived from structures:ObjectType* (REF, EXT)]({{ url }}#rule_10-2)
* [Rule 10-3, *RoleOf element type is an object type* (REF, EXT)]({{ url }}#rule_10-3)
* [Rule 10-4, *Only object type has RoleOf element* (REF, EXT)]({{ url }}#rule_10-4)
* [Rule 10-5, *RoleOf elements indicate the base types of a role type* (REF, EXT, INS)]({{ url }}#rule_10-5)
* [Rule 10-6, *Instance of RoleOf element indicates a role object* (INS)]({{ url }}#rule_10-6)
* [Rule 10-7, *Import of external namespace has data definition* (REF, EXT)]({{ url }}#rule_10-7)
* [Rule 10-8, *External adapter type has indicator* (REF, EXT)]({{ url }}#rule_10-8)
* [Rule 10-9, *Structure of external adapter type definition follows pattern* (REF, EXT)]({{ url }}#rule_10-9)
* [Rule 10-10, *Element use from external adapter type defined by external schema documents* (REF, EXT)]({{ url }}#rule_10-10)
* [Rule 10-11, *External adapter type not a base type* (REF, EXT)]({{ url }}#rule_10-11)
* [Rule 10-12, *External adapter type not a base type* (SET)]({{ url }}#rule_10-12)
* [Rule 10-13, *External attribute use only in external adapter type* (REF)]({{ url }}#rule_10-13)
* [Rule 10-14, *External attribute use has data definition* (REF, EXT)]({{ url }}#rule_10-14)
* [Rule 10-15, *External attribute use not an ID* (SET)]({{ url }}#rule_10-15)
* [Rule 10-16, *External element use has data definition* (REF, EXT)]({{ url }}#rule_10-16)
* [Rule 10-17, *Name of code type ends in CodeType* (REF, EXT)]({{ url }}#rule_10-17)
* [Rule 10-18, *Code type corresponds to a code list* (REF, EXT)]({{ url }}#rule_10-18)
* [Rule 10-19, *Element of code type has code representation term* (REF, EXT)]({{ url }}#rule_10-19)
* [Rule 10-20, *Proxy type has designated structure* (REF, EXT)]({{ url }}#rule_10-20)
* [Rule 10-21, *Association type derived from structures:AssociationType* (REF, EXT)]({{ url }}#rule_10-21)
* [Rule 10-22, *Association element type is an association type* (REF, EXT)]({{ url }}#rule_10-22)
* [Rule 10-23, *Augmentable type has augmentation point element* (REF)]({{ url }}#rule_10-23)
* [Rule 10-24, *Augmentable type has at most one augmentation point element* (REF, EXT)]({{ url }}#rule_10-24)
* [Rule 10-25, *Augmentation point element corresponds to its base type* (REF, EXT)]({{ url }}#rule_10-25)
* [Rule 10-26, *An augmentation point element has no type* (REF, EXT)]({{ url }}#rule_10-26)
* [Rule 10-27, *An augmentation point element has no substitution group* (REF, EXT)]({{ url }}#rule_10-27)
* [Rule 10-28, *Augmentation point element is only referenced by its base type* (REF, EXT)]({{ url }}#rule_10-28)
* [Rule 10-29, *Augmentation point element use is optional* (REF)]({{ url }}#rule_10-29)
* [Rule 10-30, *Augmentation point element use is unbounded* (REF)]({{ url }}#rule_10-30)
* [Rule 10-31, *Augmentation point element use must be last element in its base type* (REF, EXT)]({{ url }}#rule_10-31)
* [Rule 10-32, *Element within instance of augmentation type modifies base* (INS)]({{ url }}#rule_10-32)
* [Rule 10-33, *Only an augmentation type name ends in AugmentationType* (REF, EXT)]({{ url }}#rule_10-33)
* [Rule 10-34, *Schema component with name ending in AugmentationType is an augmentation type (REF, EXT)]({{ url }}#rule_10-34)
* [Rule 10-35, *Type derived from structures:AugmentationType is an augmentation type* (REF, EXT)]({{ url }}#rule_10-35)
* [Rule 10-36, *Augmentation element type is an augmentation type* (REF, EXT)]({{ url }}#rule_10-36)
* [Rule 10-37, *Augmentation elements are not used directly* (REF, SET)]({{ url }}#rule_10-37)
* [Rule 10-38, *Metadata type has data about data* (REF, EXT)]({{ url }}#rule_10-38)
* [Rule 10-39, *Metadata types are derived from structures:MetadataType* (REF, EXT)]({{ url }}#rule_10-39)
* [Rule 10-40, *Metadata element declaration type is a metadata type* (REF, EXT)]({{ url }}#rule_10-40)
* [Rule 10-41, *Metadata element has applicable elements* (REF, EXT, SET)]({{ url }}#rule_10-41)
* [Rule 10-42, *Name of element that ends in Representation is abstract* (REF, EXT)]({{ url }}#rule_10-42)
* [Rule 10-43, *A substitution for a representation element declaration is a value for a type* (REF, EXT)]({{ url }}#rule_10-43)
* [Rule 10-44, *Schema component name composed of English words* (REF, EXT)]({{ url }}#rule_10-44)
* [Rule 10-45, *Schema component names have only specific characters* (REF, EXT)]({{ url }}#rule_10-45)
* [Rule 10-46, *Punctuation in component name is a separator* (REF, EXT)]({{ url }}#rule_10-46)
* [Rule 10-47, *Names use camel case* (REF, EXT)]({{ url }}#rule_10-47)
* [Rule 10-48, *Attribute name begins with lower case letter* (REF, EXT)]({{ url }}#rule_10-48)
* [Rule 10-49, *Name of schema component other than attribute and proxy type begins with upper case letter* (REF, EXT)]({{ url }}#rule_10-49)
* [Rule 10-50, *Names use common abbreviations* (REF, EXT)]({{ url }}#rule_10-50)
* [Rule 10-51, *Local term declaration is local to its schema document* (REF, EXT)]({{ url }}#rule_10-51)
* [Rule 10-52, *Local terminology interpretation* (REF, EXT)]({{ url }}#rule_10-52)
* [Rule 10-53, *Singular form is preferred in name* (REF, EXT)]({{ url }}#rule_10-53)
* [Rule 10-54, *Present tense is preferred in name* (REF, EXT)]({{ url }}#rule_10-54)
* [Rule 10-55, *Name does not have nonessential words* (REF, EXT)]({{ url }}#rule_10-55)
* [Rule 10-56, *Element or attribute name follows pattern* (REF, EXT)]({{ url }}#rule_10-56)
* [Rule 10-57, *Object-class term identifies concrete category* (REF, EXT)]({{ url }}#rule_10-57)
* [Rule 10-58, *Property term describes characteristic or subpart* (REF, EXT)]({{ url }}#rule_10-58)
* [Rule 10-59, *Name may have multiple qualifier terms* (REF, EXT)]({{ url }}#rule_10-59)
* [Rule 10-60, *Name has minimum necessary number of qualifier terms* (REF, EXT)]({{ url }}#rule_10-60)
* [Rule 10-61, *Order of qualifiers is not significant* (REF, EXT)]({{ url }}#rule_10-61)
* [Rule 10-62, *Redundant term in name is omitted* (REF, EXT)]({{ url }}#rule_10-62)
* [Rule 10-63, *Element with simple content has representation term* (REF, EXT)]({{ url }}#rule_10-63)
* [Rule 10-64, *Element with complex content has representation term when appropriate* (REF, EXT)]({{ url }}#rule_10-64)
* [Rule 10-65, *Element with complex content has representation term only when appropriate* (REF, EXT)]({{ url }}#rule_10-65)
* [Rule 10-66, *Machine-readable annotations are valid* (REF, EXT)]({{ url }}#rule_10-66)
* [Rule 10-67, *Component marked as deprecated is deprecated component* (REF, EXT)]({{ url }}#rule_10-67)
* [Rule 10-68, *Deprecated annotates schema component* (REF, EXT)]({{ url }}#rule_10-68)
* [Rule 10-69, *External import indicator annotates import* (REF, EXT)]({{ url }}#rule_10-69)
* [Rule 10-70, *External adapter type indicator annotates complex type* (REF, EXT)]({{ url }}#rule_10-70)
* [Rule 10-71, *appinfo:appliesToTypes annotates metadata element* (REF, EXT)]({{ url }}#rule_10-71)
* [Rule 10-72, *appinfo:appliesToTypes references types* (SET)]({{ url }}#rule_10-72)
* [Rule 10-73, *appinfo:appliesToElements annotates metadata element* (REF, EXT)]({{ url }}#rule_10-73)
* [Rule 10-74, *appinfo:appliesToElements references elements* (SET)]({{ url }}#rule_10-74)
* [Rule 10-75, *appinfo:LocalTerm annotates schema* (REF, EXT)]({{ url }}#rule_10-75)
* [Rule 10-76, *appinfo:LocalTerm has literal or definition* (REF, EXT)]({{ url }}#rule_10-76)
* [Rule 10-77, *Use structures consistent with specification* (REF, EXT, INS, SET)]({{ url }}#rule_10-77)
* [Rule 11-1, *Name of type ends in Type* (REF, EXT)]({{ url }}#rule_11-1)
* [Rule 11-2, *Base type definition defined by conformant schema* (REF, EXT)]({{ url }}#rule_11-2)
* [Rule 11-3, *Name of simple type ends in SimpleType* (REF, EXT)]({{ url }}#rule_11-3)
* [Rule 11-4, *Use lists only when data is uniform* (REF, EXT)]({{ url }}#rule_11-4)
* [Rule 11-5, *List item type defined by conformant schemas* (REF, EXT)]({{ url }}#rule_11-5)
* [Rule 11-6, *Union member types defined by conformant schemas* (REF, EXT)]({{ url }}#rule_11-6)
* [Rule 11-7, *Name of a code simple type ends in CodeSimpleType* (REF, EXT)]({{ url }}#rule_11-7)
* [Rule 11-8, *Code simple type corresponds to a code list* (REF, EXT)]({{ url }}#rule_11-8)
* [Rule 11-9, *Attribute of code simple type has code representation term* (REF, EXT)]({{ url }}#rule_11-9)
* [Rule 11-10, *Complex type with simple content has structures:SimpleObjectAttributeGroup (REF, EXT)]({{ url }}#rule_11-10)
* [Rule 11-11, *Element type does not have a simple type name* (REF, EXT)]({{ url }}#rule_11-11)
* [Rule 11-12, *Element type is from conformant namespace* (REF, EXT)]({{ url }}#rule_11-12)
* [Rule 11-13, *Name of element that ends in Abstract is abstract* (REF, EXT)]({{ url }}#rule_11-13)
* [Rule 11-14, *Name of element declaration with simple content has representation term* (REF, EXT)]({{ url }}#rule_11-14)
* [Rule 11-15, *Name of element declaration with simple content has representation term* (SET)]({{ url }}#rule_11-15)
* [Rule 11-16, *Element substitution group defined by conformant schema* (REF, EXT)]({{ url }}#rule_11-16)
* [Rule 11-17, *Attribute type defined by conformant schema* (REF, EXT)]({{ url }}#rule_11-17)
* [Rule 11-18, *Attribute name uses representation term* (REF, EXT)]({{ url }}#rule_11-18)
* [Rule 11-19, *Element or attribute declaration introduced only once into a type* (REF, EXT)]({{ url }}#rule_11-19)
* [Rule 11-20, *Element reference defined by conformant schema* (REF, EXT)]({{ url }}#rule_11-20)
* [Rule 11-21, *Referenced attribute defined by conformant schemas* (REF, EXT)]({{ url }}#rule_11-21)
* [Rule 11-22, *Schema uses only known attribute groups* (REF, EXT)]({{ url }}#rule_11-22)
* [Rule 11-23, *Data definition does not introduce ambiguity* (REF, EXT)]({{ url }}#rule_11-23)
* [Rule 11-24, *Object class has only one meaning* (REF, EXT)]({{ url }}#rule_11-24)
* [Rule 11-25, *Data definition of a part does not redefine the whole* (REF, EXT)]({{ url }}#rule_11-25)
* [Rule 11-26, *Do not leak representation into data definition* (REF, EXT)]({{ url }}#rule_11-26)
* [Rule 11-27, *Data definition follows 11179-4 requirements* (REF, EXT)]({{ url }}#rule_11-27)
* [Rule 11-28, *Data definition follows 11179-4 recommendations* (REF, EXT)]({{ url }}#rule_11-28)
* [Rule 11-29, *Standard opening phrase for augmentation point element data definition* (REF, EXT)]({{ url }}#rule_11-29)
* [Rule 11-30, *Standard opening phrase for augmentation element data definition* (REF, EXT)]({{ url }}#rule_11-30)
* [Rule 11-31, *Standard opening phrase for metadata element data definition* (REF, EXT)]({{ url }}#rule_11-31)
* [Rule 11-32, *Standard opening phrase for association element data definition* (REF, EXT)]({{ url }}#rule_11-32)
* [Rule 11-33, *Standard opening phrase for abstract element data definition* (REF, EXT)]({{ url }}#rule_11-33)
* [Rule 11-34, *Standard opening phrase for date element or attribute data definition* (REF, EXT)]({{ url }}#rule_11-34)
* [Rule 11-35, *Standard opening phrase for quantity element or attribute data definitio*n (REF, EXT)]({{ url }}#rule_11-35)
* [Rule 11-36, *Standard opening phrase for picture element or attribute data definition* (REF, EXT)]({{ url }}#rule_11-36)
* [Rule 11-37, *Standard opening phrase for indicator element or attribute data definition (REF, EXT)]({{ url }}#rule_11-37)
* [Rule 11-38, *Standard opening phrase for identification element or attribute data definition* (REF, EXT)]({{ url }}#rule_11-38)
* [Rule 11-39, *Standard opening phrase for name element or attribute data definition* (REF, EXT)]({{ url }}#rule_11-39)
* [Rule 11-40, *Standard opening phrase for element or attribute data definition* (REF, EXT)]({{ url }}#rule_11-40)
* [Rule 11-41, *Standard opening phrase for association type data definition* (REF, EXT)]({{ url }}#rule_11-41)
* [Rule 11-42, *Standard opening phrase for augmentation type data definition* (REF, EXT)]({{ url }}#rule_11-42)
* [Rule 11-43, *Standard opening phrase for metadata type data definition* (REF, EXT)]({{ url }}#rule_11-43)
* [Rule 11-44, *Standard opening phrase for complex type data definition* (REF, EXT)]({{ url }}#rule_11-44)
* [Rule 11-45, *Standard opening phrase for simple type data definition* (REF, EXT)]({{ url }}#rule_11-45)
* [Rule 11-46, *Same namespace means same components* (REF, EXT)]({{ url }}#rule_11-46)
* [Rule 11-47, *Different version means different view* (REF, EXT)]({{ url }}#rule_11-47)
* [Rule 11-48, *Reference schema document imports reference schema document* (SET)]({{ url }}#rule_11-48)
* [Rule 11-49, *Extension schema document imports reference or extension schema document* (SET)]({{ url }}#rule_11-49)
* [Rule 11-50, *Structures imported as conformant* (REF, EXT)]({{ url }}#rule_11-50)
* [Rule 11-51, *XML namespace imported as conformant* (REF, EXT)]({{ url }}#rule_11-51)
* [Rule 11-52, *Each namespace may have only a single root schema in a schema set* (SET)]({{ url }}#rule_11-52)
* [Rule 11-53, *Consistently marked namespace imports* (REF, EXT)]({{ url }}#rule_11-53)
* [Rule 12-1, *Instance must be schema-valid* (INS)]({{ url }}#rule_12-1)
* [Rule 12-2, *Empty content has no meaning* (INS)]({{ url }}#rule_12-2)
* [Rule 12-3, *Element has only one resource identifying attribute* (INS)]({{ url }}#rule_12-3)
* [Rule 12-4, *Attribute structures:ref must reference structures:id* (INS)]({{ url }}#rule_12-4)
* [Rule 12-5, *Linked elements have same validation root* (INS)]({{ url }}#rule_12-5)
* [Rule 12-6, *Attribute structures:ref references element of correct type* (INS)]({{ url }}#rule_12-6)
* [Rule 12-7, *structures:uri denotes resource identifier* (INS)]({{ url }}#rule_12-7)
* [Rule 12-8, *structures:id and structures:id denote resource identifier* (INS)]({{ url }}#rule_12-8)
* [Rule 12-9, *Nested elements and references have the same meaning.* (INS)]({{ url }}#rule_12-9)
* [Rule 12-10, *Metadata applies to referring entity* (INS)]({{ url }}#rule_12-10)
* [Rule 12-11, *Referent of structures:relationshipMetadata annotates relationship* (INS)]({{ url }}#rule_12-11)
* [Rule 12-12, *Values of structures:metadata refer to values of structures:id* (INS)]({{ url }}#rule_12-12)
* [Rule 12-13, *Values of structures:relationshipMetadata refer to values of structures:i*d (INS)]({{ url }}#rule_12-13)
* [Rule 12-14, *structures:metadata and structures:relationshipMetadata refer to metadata elements* (INS)]({{ url }}#rule_12-14)
* [Rule 12-15, *Attribute structures:metadata references metadata element* (INS)]({{ url }}#rule_12-15)
* [Rule 12-16, *Attribute structures:relationshipMetadata references metadata element* (INS)]({{ url }}#rule_12-16)
* [Rule 12-17, *Metadata is applicable to element* (INS)]({{ url }}#rule_12-17)
{: class="list-unstyled" style="margin-top: 1em;"}

---

{% assign url = site.data.links.code_list_spec %}

<h4 id="cl" style="padding-top: 65px; margin-top: -65px;"><a href="{{ url }}">Code Lists Specification</a></h4>

The NIEM Code Lists specification defines 29 normative rules.  These rules apply to designated conformance targets, outlined below and listed at the end of each rule in parenthesis.

| Conformance Target | Description |
| ------------------ | ----------- |
| CLD | code list document |
| GC-CLD | Genericode code list document |
| CSV-CLD | CSV code list document |
| XSD | code list-enabled schema document |
| INS | code list-enabled instance document |
| VSET | code list validation set |
{:.table-auto}

* [Rule 3-1, *Code list-enabled schema document has conformance target* (XSD)]({{ url }}#rule_3-1)
* [Rule 3-2, *Document with conformance target is a code list-enabled schema document* (VSET)]({{ url }}#rule_3-2)
* [Rule 4-1, *Content in the cli namespace conforms to schema* (INS)]({{ url }}#rule_4-1)
* [Rule 4-2, *Code list URI is an absolute URI* (INS)]({{ url }}#rule_4-2)
* [Rule 4-3, *Column identifier accompanied by code list identifier* (INS)]({{ url }}#rule_4-3)
* [Rule 4-4, *Constraining indicator accompanied by code list identifier* (INS)]({{ url }}#rule_4-4)
* [Rule 4-5, *Effective run-time binding.* (INS)]({{ url }}#rule_4-5)
* [Rule 4-6, *Content in the clsa namespace conforms to schema* (XSD)]({{ url }}#rule_4-6)
* [Rule 4-7, *Elements are xs:appinfo annotations* (XSD)]({{ url }}#rule_4-7)
* [Rule 4-8, *Code list URI is absolute URI* (XSD)]({{ url }}#rule_4-8)
* [Rule 4-9, *Simple code list binding to schema components* (XSD)]({{ url }}#rule_4-9)
* [Rule 4-10, *Complex code list binding to schema components* (XSD)]({{ url }}#rule_4-10)
* [Rule 4-11, *Attribute declaration effective simple binding* (VSET)]({{ url }}#rule_4-11)
* [Rule 4-12, *Element declaration effective simple binding* (VSET)]({{ url }}#rule_4-12)
* [Rule 4-13, *Type definition effective simple binding* (VSET)]({{ url }}#rule_4-13)
* [Rule 4-14, *Element declaration effective complex binding* (VSET)]({{ url }}#rule_4-14)
* [Rule 4-15, *Complex type definition effective complex binding* (VSET)]({{ url }}#rule_4-15)
* [Rule 4-16, *Matches and validity for a code list binding* (VSET)]({{ url }}#rule_4-16)
* [Rule 4-17, *Value comparisons based on types* (VSET)]({{ url }}#rule_4-17)
* [Rule 4-18, *Code list identified by candidate code list identifiers* (VSET)]({{ url }}#rule_4-18)
* [Rule 5-1, *CSV code list document is a CSV file* (CSV-CLD)]({{ url }}#rule_5-1)
* [Rule 5-2, *CSV code list document has header* (CSV-CLD)]({{ url }}#rule_5-2)
* [Rule 5-3, *CSV column name is not empty* (CSV-CLD)]({{ url }}#rule_5-3)
* [Rule 5-4, *CSV file as a code list document* (CSV-CLD)]({{ url }}#rule_5-4)
* [Rule 6-1, *Genericode code list document defined by Genericode* (GC-CLD)]({{ url }}#rule_6-1)
* [Rule 6-2, *Document with conformance target is Genericode code list document* (VSET)]({{ url }}#rule_6-2)
* [Rule 6-3, *Genericode code list document is schema-valid* (GC-CLD)]({{ url }}#rule_6-3)
* [Rule 6-4, *XML Schema alternate datatypes are treated the same as built in datatype*s (GC-CLD)]({{ url }}#rule_6-4)
* [Rule 6-5, *Genericode file as a code list document* (GC-CLD)]({{ url }}#rule_6-5)
{: class="list-unstyled" style="margin-top: 1em;"}