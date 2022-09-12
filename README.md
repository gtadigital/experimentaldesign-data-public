# experimentaldesign-data-public
 
## Abstract
See https://data.snf.ch/grants/grant/179095
 
## Method
The present data set includes both the source data (a) and the research data (b) resulting from the SNSF-funded research project »Experimental Design in the Post-War Period - Heinz Isler's (1926-2009). Contribution in the Perspective of the History of Engineering and Culture«: 
	
a) Source data have been collected within the gta Collections Management System (CMS, https://collections.gta.arch.ethz.ch/). They include both the holding data of the Heinz Isler bequest (gta Archives/ETH Zurich) and scholarly observation  that have been collected as part of the research project. Source data are provided as full XML export from the Collection Management System. 

b) research data consist of a transformation of holding data and related scholarly observation into a machine-processable RDF format for FAIR access and reuse. As the general underlying ontology, the ISO certified Conceptual Reference Model (CRM) of International Committee for Documentation (CIDOC) of the International Council of Museums (ICOM) is being used (https://www.cidoc-crm.org/). The data model for the actual mapping complies with Bruseker G, Carboni, N., et al. Semantic Reference Data Models (SDRM) provided by the Swiss Art Research Infrastructures (SARI, https://docs.swissartresearch.net/). The data models specifically used are: 
Places (https://docs.swissartresearch.net/et/place/)
Persons (https://docs.swissartresearch.net/et/persons/)
Groups (https://docs.swissartresearch.net/et/group/)
Archival Units (https://docs.swissartresearch.net/et/archival/)
Digital Objects (https://docs.swissartresearch.net/et/do/)
The conceptual modelling for Built Works and Project follows Guillem, A. and Bruseker, G. Creative Processes Representation. A conceptual model extending CIDOC CRM and FRBR for the description of creative processes, 2019 (https://github.com/Habennin/crmcpr). 

The transformation of the source data is using 3M modelling software for content mapping and X3ML (https://www.ics.forth.gr/isl/x3ml-toolkit) for data transformation. For validating and visualisation purpose, the data are being ingested into the open source Semantic Linked Data Platform ResearchSpace (https://github.com/researchspace/researchspace). 

The present data set includes all data available at the project end. An updated version of the same data will be available at GitHub (https://github.com/gtadigital/experimentaldesign-data-public). The later will include additional data and data visualisation related to the planned book publication as soon as available (due 2023).     
