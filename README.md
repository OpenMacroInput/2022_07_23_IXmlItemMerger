# 2022_07_23_IXmlItemMerger
This tools merge xml files into one big file then split all the first item by name. It is one of the two ways to setup an OMI module.


For example you have two file A_OMI.xml and B_OMI.xml

```
<xml> 
  <itemA ...></itemA>
  <itemB .../>
  <itemB .../>
  <itemB>...</itemB>
<xml>
```
Will give you and array of one 'itema' and three 'itemb' where the XML as a new XML or split text of XML item text are readable in the lib.


The idea here, is to allows any module to be add in the XML.
It let's the user choose what name of file he want but at the end it merge in a big xml one split in class to be read.

See also: 2022_07_23_IFileExtensionMerger that works in a similar ways by based on file extension.
