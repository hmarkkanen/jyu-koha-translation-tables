# Voyager-Koha MMT translation rules for University of Jyväskylä library

To be used with [Koha Migration Toolbox](https://github.com/kivilahtio/koha-migration-toolbox) by Olli-Antti Kivilahti, National Library of Finland

* For extracting data for development and testing, run: ./extract.pl --bound -A -B -H --noanonymize --precision=1 > & extract.log

* Remember to store extracted data securely, as --noanonymize option makes extracted files to include personally identifiable information!


* rules-jyu -- Usemarcon rules for MARC data transformation
* tests -- YAML files for test cases
* translationTables - YAML files for Voyager->Koha value mappings