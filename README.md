# blueprism-schemas

These are XML Schemas for the Blue Prism file formats and follow the specification of XSD 1.1 from the W3C in 2012. 
It was created by hand because Blue Prism was not providing schemas at the time of the initial commit and auto-generated
XSD from exiting XML files were found to lack a maintainable and comprehensible quality. The schemas were tested against
exported XML files using an XSD 1.1 library.

Please keep in mind that these schemas are written after the version 1.1 of XSD, which seems to be less popular and
therefore less often supported by libraries. This choice has been made because XSD 1.1 is less restrictive and allows
a more dynamic specification of XML documents.

## **PLEASE NOTE**
Blue Prism is a registered trademark of Blue Prism Ltd. The authors of this repository are not affiliated with 
Blue Prism in any way. All provided source code and documentation related to products of Blue Prism Ltd. was created 
purely by analyzing publicly available XML files and without knowledge of any non-public aspects of their products.