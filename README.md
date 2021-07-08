# Robert Minter Collection

Source: http://www.open.ac.uk/Arts/minter/index.php

## Generate result set XMLs from HTM L tables
```
fx -q queries/scrape-table.sparql -v page=1...53 -p data/page_?page.xml -f XML
```