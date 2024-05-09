# tap3xml
tap3xml is a both directions XML&lt;->TAP3 converter made in C++. It will convert the files according to the ASN.1 structure defined by the GSM Association.  Unfortunately, because of lack of resources, I am not able to test tap3xml properly. If you like to contribute with the improvement of the tool, you can send me your ideas/comments/bugs.

# build on windows :
1- install gcc from winlibs.com
2- run this command
```
g++ -o tap3xml -g -Wall -Wno-unknown-pragmas global.cpp Buffin.cpp Buffout.cpp Asn.cpp AsnItem.cpp TreeItem.cpp TreeParser.cpp Xml.cpp XmlItem.cpp asn1_lexer.cpp asn1_parser.cpp xml_lexer.cpp xml_parser.cpp tap3xml.cpp TapInfo.cpp
```

