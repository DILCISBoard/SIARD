# SIARD
Here you will find the SIARD specifications along with XML schemas and examples (as files).

You will also find the recommendation for the SIARD 2.0 feature of storing large objects outside the SIARD archive file along with examples.

Here is also a short list of references to tools supporting SIARD.

SIARD (Software Independent Archival of Relational Databases) is a normative description of an open file format for the long-term archiving of relational databases. SIARD is a nonproprietary, published open standard. The SIARD format is based on open standards, including the ISO standards Unicode, XML, and SQL, the URI Internet standard, and the industry standard ZIP. The aim of employing internationally recognised standards is to ensure the long-term preservation of, and access to, the widely used relational database model, as well as easy exchange of database content, independent of proprietary “dump” formats.

SIARD was developed as part of the Swiss Federal Archives (SFA) ARELDA project (ARchiving of ELectronic DAta) (2000-2004) and based on the archiving strategy of the ARELDA project of 11 April 2006.
The SIARD 1.0 format was developed in 2008 by the Swiss Federal Archives and in May 2008 SIARD 1.0 was accepted as the official format for archiving relational databases of the European Open PLANETS project in which the SFA participated.

The SIARD 2.0 format was developed in 2015 by the Swiss Federal Archives and the [E-ARK project](http://www.eark-project.com/).

The SIARD 2.1 format was developed in 2018 by the SFA after the end of the E-ARK project.

SIARD 1.0 and 2.0 are also official Swiss E-Government Standards and version 1.0 can be found [here](https://www.ech.ch/vechweb/page?p=dossier&documentNumber=eCH-0165&documentVersion=2.0) and version 2.0 [here](https://github.com/DILCISBoard/SIARD/blob/master/SIARD%202.0/format/2016-06-01/STAN_e_DEF_2016-08-02_eCH-0165_V2.0_SIARD-Format.pdf). (version 2.0 is currently not available at ech.ch).

SIARD 2.1 is not an official Swiss E-Government Standard, but can be found [here](https://www.bar.admin.ch/dam/bar/de/dokumente/kundeninformation/siard_formatbeschreibung.pdf.download.pdf/siard_formatbeschreibung.pdf  
) at the SFA website.

SIARD 2.1.1. is a correction to SIARD 2.1

The development and release of new versions will be coordinated in the DILCIS board (associated with the DLM Forum, created by the EC in 1994) following procedures proposed by the SFA.

The SFA is represented in the DILCIS board (as well as in DLM Forum) together with other national archives using SIARD.

SIARD 2.2 adds support for files outside the database according to part 9 of SQL:2008 (ISO/IEC 9075-9:2008 – SQL/MED) as well as scalability supporting large objects stored outside the SIARD file. Apart from this it is identical to version 2.1.1.
It has been developed by the DILCIS Board during the E-ARK3 project.

## Specifications

- SIARD 1.0   [2008-09-30](https://github.com/DILCISBoard/SIARD/blob/master/SIARD%201.0/format/2008-09-30/)
- SIARD 2.0   [2016-06-01](https://github.com/DILCISBoard/SIARD/blob/master/SIARD%202.0/format/2016-06-01/)
- SIARD 2.1   [2018-02-15](https://github.com/DILCISBoard/SIARD/blob/master/SIARD%202.1/format/2018-02-15/)
- SIARD 2.1.1 [2019-05-15](https://github.com/DILCISBoard/SIARD/blob/master/SIARD%202.1/format/2018-02-15/)
- SIARD 2.2   [2021-08-31](https://github.com/DILCISBoard/SIARD/blob/master/SIARD_2-2/format/2021-08-31/)


<!-- 
## Recommendations

Recommendation for storing large objects outside the SIARD file ver 0.28 [2018-08-28](https://github.com/DILCISBoard/SIARD/tree/master/SIARD%202.1/recommendations/lobs%20outside%20the%20SIARD%20file/0.28)
Available in formats
[Github Markdown](/SIARD%202.1/recommendations/lobs%20outside%20the%20SIARD%20file/0.28/Recommendation%20for%20storing%20large%20object%20outside%20the%20SIARD%20file.gfm.md),
[PDF](/SIARD%202.1/recommendations/lobs%20outside%20the%20SIARD%20file/0.28/Recommendation%20for%20storing%20large%20objects%20outside%20the%20SIARD%20file%20ver%200.28.gd.pdf)
and [Open Document Text](/SIARD%202.1/recommendations/lobs%20outside%20the%20SIARD%20file/0.28/Recommendation%20for%20storing%20large%20objects%20outside%20the%20SIARD%20file%20ver%200.28.gd.odt)
-->

## Guideline and tools
Information on how to package SIARD files into SIPs, AIPs and DIPs can be found at the CITS SIARD repository https://github.com/DILCISBoard/CITS-SIARD. Here you will also find links to tools that create and read SIARD files.
