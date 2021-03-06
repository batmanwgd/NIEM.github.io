---
  title: Elements
  icon: fa-database
  description: An element represents a concept.  In an instance, it acts as a container  that may carry either a simple value or an object, and optionally attributes.
  links:
  - url: /reference/concepts/property/element/modeling/
  - url: /reference/concepts/property/element/xml/
  - url: /reference/concepts/property/element/json/
---

An element represents a concept.  In an instance, it acts as a container that may carry either simple content (a value) or complex content (an object).  In either case, an element can also carry attributes.

{: .example}
- Core defines element `nc:PersonGivenName`.  This element will carry simple content, for example, a value like "Jane".
- Core also defines element `nc:Person`.  This element will carry complex content - a set of sub-elements representing properties like name, age, height, and employment information.

<!--more-->
