# Changes

### \[v3.7.0\] 2021-08-16

Added:

- `if` function is added. Sample `if(condition , truestatement , falsestatement)`

### \[v3.6.0\] 2021-07-26

Added:

- `DataSetIndex` now can let consumer to know if given variable path has multiple data permutations.
  
### \[v3.5.0\] 2021-07-10

Added:

- Implemented a new JSON Data Set indexer `DataSetIndex.index(jsonObject)`. It is a substantially 
  faster alternative to `JsonDataSetMaker`.  

### \[v3.4.0\] 2021-04-16

Updated:

- Operator `!` on `null` values will now yield `null`, as suppose to `true`.

Added:

- Added `CHANGELOG.md` file. 
- KEEP_COMPLEX_ARRAYS mode for JsonDataSetMaker. This mode allows preserving object 
  arrays for easier JSON reconstructions.
  
  