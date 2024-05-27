# replication-package-OTPr

## VOSviewer setup

1. Open VOSviewer 
2. Create map based on bibliographic data
3. Read data from reference manager files
4. Choose scopus.ris file

### Co-authorship
1. Select "Co-authorship" as type of analysis
2. Leave all default options
3. Set minimum number of documents of author equal to 1
4. VOSviewer found the larger set of connected items consisting of 14 items. Click on Yes to show this set
5. The image is saved in images/coauthor_14_connected_items.png; The map file is saved in map/coauthor_14_connected_items.txt

### Co-occurrences (threshold = 1 )
1. Select "Co-occurrence" as type of analysis
2. Import keyword_all_mask.txt as theasaurus file
3. Set minimum number of occurrence of author equal to 1
4. The image is saved in images/keyword_all.png; The map file is saved in map/keyword_all_map.txt

### Co-occurrences (threshold = 5 )
1. Select "Co-occurrence" as type of analysis
2. Import keyword_all_mask.txt as theasaurus file
3. Set minimum number of occurrence of author equal to 5
4. The image is saved in images/keyword_5_occurrences.png; The map file is saved in map/keyword_5_occurrences.txt
