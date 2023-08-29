This folder contains the species mappings between the names in the germplasm's database and the accepted names found using [GBIF's species lookup tool](https://www.gbif.org/tools/species-lookup ).
The [file itself](GermplasmBankSpeciesMapping.csv) contains three columns:
  1. **Database name**: The species name as it appears on the germplasm's database.
  3. **Accepted name**: The species name, as it is accepted and appears in GBIF's taxonomy.
  4. **Difference**: The distinction between the database name and the accepted name. Can take the following value or combination of values:
     * *SYNONYM*: the database name is a synonym of the accepted species.
     * *Genus*: the database name could only be matched up to genus level using GBIF's species lookup took.
     * *Typo*: the database name contained some typing mistake.
     * *Needs revision*: the accepted name needs expert revision.
