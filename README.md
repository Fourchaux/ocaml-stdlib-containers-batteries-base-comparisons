# Core functions comparison

OCaml Stdlib (v4.12.0), Containers (v3.3), Batteries (v3.3.0) and Base (v0.14.1) libraries.

Comparisons of the main functions (with their simplified signatures) used in the following core modules:
- Array_ArrayLabels
- List_ListLabels
- Map
- Option
- Printf
- Result
- Seq
- Set
- String_StringLabels

Note 1: the .csv files are using the TAB (\t) field separator.

Note 2 : ALL.csv - the original file

Note 3 : Functions only found in Containers/Batteries/Base:
- stdlib_diffs3: Same functions available in the 3 libraries 
- stdlib_diffs2: Same functions available in 2 libraries 
- stdlib_diffs1: Functions available in one of the 3 libraries 

Note 4 : Containers vs Batteries/Base:
- containers_diffs2: Same functions available in Batteries and Base (not in Containers)
- containers_diffs1: Functions available in Batteries or Base (not in Containers)
