# San Francisco Trees

## Data sets

### [sf_trees.csv](https://github.com/chrisyifanjin/RforDataScience-Projects/blob/master/San%20Francisco%20Trees/Data/sf_trees.csv) 

A full data dictionary is available at: [the source](https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq) but it's fairly sparse.

|variable     |class     |description |
|:------------|:---------|:-----------|
|tree_id      |double    | Unique ID |
|legal_status |character | LegalLegal staus: Permitted or DPW maintained |
|species      |character | Tree species includes common name after the :: separator |
|address      |character | Street Address |
|site_order   |double    | Order of tree at address where multiple trees are at same address. Trees are ordered in ascending
address order |
|site_info    |character | Site Info - Where the tree resides |
|caretaker    |character | Agency or person that is primary caregiver to tree -- Owner of Tree |
|date         |double    | Date Planted (NA if before 1955)|
|dbh          |double    | depth, height|
|plot_size    |character | Dimension of plot - typically in feet |
|latitude     |double    | Latitude |
|longitude    |double    | Longitude |

### [Street_Tree_Map](https://github.com/chrisyifanjin/RforDataScience-Projects/blob/master/San%20Francisco%20Trees/Data/Street_Tree_Map.csv)
