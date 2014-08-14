## EMAIL SENT

* Global Biodiversity Information Facility (GBIF)	Species occurrence data	rgbif - SENT
* Dryad	Repository for published data sets	rdryad  - SENT
* eBird	Global tools for birders, critical data for science	rebird  - SENT
* BEF Data Portal	Data from the forest Biodiversity and Ecosystem Functioning (BEF) experiment	rbefdata  - SENT
* OpenFisheries database	A platform for aggregating global fishery data	rfisheries  - SENT
* Mendeley	Mendeley is a free reference manager and academic social network	RMendeley  - SKIPPING
* World Bank Climate Data	World Bank climate data used in the World Bank	rWBclimate   - SKIPPING
* Treebase	Repository of user-submitted phylogenetic trees and data to generate them	treeBASE   - SENT
* Fishbase	A Global Information System on Fishes	rfishbase   - SENT
* USA National Phenology Network	Repository of phenology data	rnpn   - SENT
* Encyclopedia of Life (EOL)	Global access to knowledge about life on Earth	taxize 
* Integrated Taxonomic Information Service (ITIS)	Taxonomic information on plants, animals, fungi, and microbes of mostly North America	taxize  - SENT
* openSNP.org	Repository of SNP data	rsnps  - SENT
* Biodiversity Heritage Library	Making biodiversity literature openly available to the world	rbhl   - SENT
* Datacite	Metadata on datasets	rdatacite  - SENT
	* from datacite: I could offer you a list of all deposit timestamps (~1.6M). You can count, aggregate, or group them on your end with any granularity you need. API call is as follows (results list is unsorted!):  http://search.datacite.org/api?q=*&fl=uploaded&wt=csv&csv.header=false&fq=has_metadata:true&rows=99 , Just increase the row count (e.g. to 9999999) to get all records.
* Figshare	Repository of research outputs (papers, figures, datasets)	rfigshare  - SENT
* VertNet	Vertebrate specimen data	rvertnet  - SENT
* Theplantlist dot org	Working list of all known plant species	taxize  - SENT
	* They said the plant list is mostly static, but kew plant list and another they manage do grow, so will get data on those from them
* Neotoma	Databases of paleoecological data	neotoma  - SENT
* uBio	Indexing & Organizing Biological Names	taxize  - SENT
* Tropicos (from Missouri Botanical Garden)	Nomenclatural data from the Missouri Botanical Garden	taxize  - SENT
* Catalogue of Life	List of the world's known species of animals, plants, fungi and micro-organisms	taxize  - SENT
* NOAA climatic data	NOAA climatic data	rnoaa  - SENT
* dbSNP	NCBI SNP repository	rsnps  - SENT

## NOT SENT

* Plantminer	Web app built to make the search and processing of plant taxonomic data easier	taxize - AN AGGREGATOR, DON'T SEND
* Pubmed	Full-text and metadata	- rpubmed/rentrez
* Europe PubMed Central	Free information resource for biomedical and health researchers	- rebi
* Pensoft	Full-text and metadata	rpensoft 
* Hindawi	Full-text and metadata	rhindawi 
* eLife	Full-text and metadata	elife - USE API TO GET NO. ARTICLES
* Public Library of Science (PLOS)	Full-text and metadata from	rplos - I THINK I CAN GET IT VIA THE SEARCH API???

## STATIC DATA, JUST LOOK AT SITE

* Phylomatic	Get a phylogeny for a given species list	taxize  - STATIC, JUST LOOK AT SITE, HOW MANY SPECIES?