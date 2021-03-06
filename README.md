# mixs-legacy
Older versions of spreadsheet formatted MIxS standard templates (up to version 5).

Note that before version 4, MIxS was not released as a single standard, but rather as a set of checklists. Those lists are available here in the folders labeled pre-2009, 2009, 2010, 2011.

Older versions of MIxS and checklists were released as .xls files. Those files are available here, along with a new version saved in the open source .xslx format. Some of the oldest files are available as .docx and .xds (in the pre-2009 folder).

**To request changes to the MIxS standards, please use the [issue tracker in the main MIxS repostiory](https://github.com/GenomicsStandardsConsortium/mixs/issues).**

# Reuse and citation of content on this repository

The MIxS standards and the content of this repo are freely available under the `Creative Commons 0 (open source) <https://creativecommons.org/share-your-work/public-domain/cc0/>`_ agreement. 

# Cite the standard

If you use any of the MIxS standards, please site [this paper] (https://www.nature.com/articles/nbt.1823):

DOI: https://doi.org/10.1038/nbt.1823

RIS format:

```
TY  - JOUR
AU  - Yilmaz, Pelin
AU  - Kottmann, Renzo
AU  - Field, Dawn
AU  - Knight, Rob
AU  - Cole, James R
AU  - Amaral-Zettler, Linda
AU  - Gilbert, Jack A
AU  - Karsch-Mizrachi, Ilene
AU  - Johnston, Anjanette
AU  - Cochrane, Guy
AU  - Vaughan, Robert
AU  - Hunter, Christopher
AU  - Park, Joonhong
AU  - Morrison, Norman
AU  - Rocca-Serra, Philippe
AU  - Sterk, Peter
AU  - Arumugam, Manimozhiyan
AU  - Bailey, Mark
AU  - Baumgartner, Laura
AU  - Birren, Bruce W
AU  - Blaser, Martin J
AU  - Bonazzi, Vivien
AU  - Booth, Tim
AU  - Bork, Peer
AU  - Bushman, Frederic D
AU  - Buttigieg, Pier Luigi
AU  - Chain, Patrick S G
AU  - Charlson, Emily
AU  - Costello, Elizabeth K
AU  - Huot-Creasy, Heather
AU  - Dawyndt, Peter
AU  - DeSantis, Todd
AU  - Fierer, Noah
AU  - Fuhrman, Jed A
AU  - Gallery, Rachel E
AU  - Gevers, Dirk
AU  - Gibbs, Richard A
AU  - Gil, Inigo San
AU  - Gonzalez, Antonio
AU  - Gordon, Jeffrey I
AU  - Guralnick, Robert
AU  - Hankeln, Wolfgang
AU  - Highlander, Sarah
AU  - Hugenholtz, Philip
AU  - Jansson, Janet
AU  - Kau, Andrew L
AU  - Kelley, Scott T
AU  - Kennedy, Jerry
AU  - Knights, Dan
AU  - Koren, Omry
AU  - Kuczynski, Justin
AU  - Kyrpides, Nikos
AU  - Larsen, Robert
AU  - Lauber, Christian L
AU  - Legg, Teresa
AU  - Ley, Ruth E
AU  - Lozupone, Catherine A
AU  - Ludwig, Wolfgang
AU  - Lyons, Donna
AU  - Maguire, Eamonn
AU  - Methé, Barbara A
AU  - Meyer, Folker
AU  - Muegge, Brian
AU  - Nakielny, Sara
AU  - Nelson, Karen E
AU  - Nemergut, Diana
AU  - Neufeld, Josh D
AU  - Newbold, Lindsay K
AU  - Oliver, Anna E
AU  - Pace, Norman R
AU  - Palanisamy, Giriprakash
AU  - Peplies, Jörg
AU  - Petrosino, Joseph
AU  - Proctor, Lita
AU  - Pruesse, Elmar
AU  - Quast, Christian
AU  - Raes, Jeroen
AU  - Ratnasingham, Sujeevan
AU  - Ravel, Jacques
AU  - Relman, David A
AU  - Assunta-Sansone, Susanna
AU  - Schloss, Patrick D
AU  - Schriml, Lynn
AU  - Sinha, Rohini
AU  - Smith, Michelle I
AU  - Sodergren, Erica
AU  - Spor, Aymé
AU  - Stombaugh, Jesse
AU  - Tiedje, James M
AU  - Ward, Doyle V
AU  - Weinstock, George M
AU  - Wendel, Doug
AU  - White, Owen
AU  - Whiteley, Andrew
AU  - Wilke, Andreas
AU  - Wortman, Jennifer R
AU  - Yatsunenko, Tanya
AU  - Glöckner, Frank Oliver
PY  - 2011
DA  - 2011/05/01
TI  - Minimum information about a marker gene sequence (MIMARKS) and minimum information about any (x) sequence (MIxS) specifications
JO  - Nature Biotechnology
SP  - 415
EP  - 420
VL  - 29
IS  - 5
AB  - Here we present a standard developed by the Genomic Standards Consortium (GSC) for reporting marker gene sequences—the minimum information about a marker gene sequence (MIMARKS). We also introduce a system for describing the environment from which a biological sample originates. The 'environmental packages' apply to any genome sequence of known origin and can be used in combination with MIMARKS and other GSC checklists. Finally, to establish a unified standard for describing sequence data and to provide a single point of entry for the scientific community to access and learn about GSC checklists, we present the minimum information about any (x) sequence (MIxS). Adoption of MIxS will enhance our ability to analyze natural genetic diversity documented by massive DNA sequencing efforts from myriad ecosystems in our ever-changing biosphere.
SN  - 1546-1696
UR  - https://doi.org/10.1038/nbt.1823
DO  - 10.1038/nbt.1823
ID  - Yilmaz2011
ER  - 
```

## Cite this repo

If you reuse code from this repository, please site the repository URL (https://github.com/GenomicsStandardsConsortium/mixs)

# General Background
Without specific guidelines, most genomic, metagenomic and marker gene sequences in databases are sparsely annotated with the information required to guide data integration, comparative studies and knowledge generation. Even with complex keyword searches, it is currently impossible to reliably retrieve sequences that have originated from certain environments or particular locations on Earth—for example, all sequences from ‘soil’ or ‘freshwater lakes’ in a certain region of the world. Because public databases of the International Nucleotide Sequence Database Collaboration (INSDC; comprising DNA Data Bank of Japan (DDBJ), the European Nucleotide Archive (EBI-ENA) and GenBank (http://www.insdc.org/)) depend on author-submitted information to enrich the value of sequence data sets, we argue that the only way to change the current practice is to establish a standard of reporting that requires contextual data to be deposited at the time of sequence submission. The adoption of such a standard would elevate the quality, accessibility and utility of information that can be collected from INSDC or any other data repository.

The GSC has defined a set of core descriptors for genomes and metagenomes in the form of a MIGS/MIMS specification. MIGS/MIMS extends the minimum information already captured by the INSDC. The recently introduced MIMARKS now captures information about marker genes. Additionally, we also introduced ‘environmental packages’ that standardize sets of measurements and observations describing particular habitats that are applicable across all GSC checklists and beyond. We define ‘environment’ as any location in which a sample or organism is found, e.g., soil, air, water, human-associated, plant-associated or laboratory. The original MIGS/MIMS checklists included contextual data about the location from which a sample was isolated and how the sequence data were produced. However, standard descriptions for a more comprehensive range of environmental parameters, which would help to better contextualize a sample, were not included. The environmental packages presented here are relevant to any genome sequence of known origin and are designed to be used in combination with MIGS, MIMS and MIMARKS checklists.

To create a single entry point to all minimum information checklists from the GSC and to the environmental packages, we created an overarching framework, the MIxS standard . MIxS includes the technology-specific checklists from the previous MIGS and MIMS standards, provides a way of introducing additional checklists such as MIMARKS, and also allows annotation of sample data using environmental packages.

The adoption of the GSC standards by major data providers and organizations, as well as the INSDC, supports efforts to contextually enrich sequence data and complements recent efforts to enrich other (meta) ‘omics data. The MIxS standards have been developed to the point that it is ready for use in the publication of sequences. A defined procedure for requesting new features and stable release cycles will facilitate implementation of the standard across the community. Compliance among authors, adoption by journals and use by informatics resources will vastly improve our collective ability to mine and integrate invaluable sequence data collections for knowledge- and application-driven research.
