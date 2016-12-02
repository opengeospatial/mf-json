![OGC Logo](http://portal.opengeospatial.org/files/?artifact_id=11976&format=gif "OGC Logo")

# Moving Features JSON Encodings 

This draft proposes a JSON encoding representation of movement of geographic features specified by OGC Moving Features ([OGC 14 083r2](http://docs.opengeospatial.org/is/14-083r2/14-083r2.html) and [OGC 14 084r2](http://docs.opengeospatial.org/is/14-084r2/14-084r2.html)).
A moving feature can be express as a dynamic geomtry whose location continouly changes over time. Also it can contain dynamic non-spatial attributes of features whose value varies with time. 
The data format in this draft is extended from **GeoJSON terms** (type, geomtery, properties, etc.) in order to take the compatibility of GeoJSON.

## About

This GitHub repository tracks the latest version of the Moving Features JSON Encoding draft, which is not an OGC Stardard but will be publishied as an OGC Best Practice Paper. Therefore, it is not an official postion of the OGC memebership.
With this repository the OGC invites collaboration and comments directed at the development and enhancement of this candidate encoding format.
Pull requests for fixes are appreciated, and new functionality will still be considered until fixing the encoding format. 
The specification is done in asciidoc a format supported by GitHub, similar to markdown but with some features that make it better for specifications, like automatic section numbering.

**Editor: Kyoung-Sook KIM, Hirotaka Ogawa**

## Contributing

The contributor understands that any contributions, if accepted by the OGC Membership, shall 
be incorporated into the formal OGC Moving Features standards document and that all copyright and 
intellectual property shall be vested to the OGC.

The Moving Features Standards Working Group (SWG) is the group at OGC responsible for the stewardship
of the standard.

The Moving Features SWG currently has the following email list:
   - moving-features.swg@lists.opengeospatial.org -- [sign up here](https://lists.opengeospatial.org/mailman/listinfo/moving-features.swg)
      - Private List
      - Access controlled archives
      - Requires OGC membership and Observer Agreement to protect IPR (intellectual property rights)


**SWG Chair:**
+ Nobuhiro ISHIMARU(Hitachi, Ltd., Defense Systems Company)
+ Ryosuke SHIBASAKI(University of Tokyo CSIS)
+ Kyoung-Sook KIM(National Institute of Advanced Industrial Science & Technology (AIST))

## Editing and commenting
The Moving Features SWG is accepting public comments and suggested revisions to this document via GitHub. 
To suggest changes to the document please fork the repository and submit a pull request with the desired changes. 
Please make one pull request per logical requested change and be sure to include a comment in the PR with any justification or reasoning on why the change is needed.

For more general comments (that don't include actual text changes to the specification) please create a GitHub [issue](https://github.com/opengeospatial/geopackage/issues) for that topic.

Complex changes and feature requests must go throught the [change request](http://portal.opengeospatial.org/public_ogc/change_request.php) process. The details entered
in the change request form will help the SWG adjudicate and prioritize the request.

## Usages
1. Install [asciidoctor](http://asciidoctor.org)
2. On command line: asciidoctor -a stylesheet=./example.css index.adoc

[Document rendering example](https://ksookim.github.io/mf-json)
[API test example] (https://ksookim.github.io/mf-access/)
