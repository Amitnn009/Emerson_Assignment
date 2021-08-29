Types of Table
==============

Consider Your Options for the Type of Table to Create
------------------------------------------------------
What types of tables can you create? Here are some choices:

================================       	=========================================================================================================================================================================================================================================================================================================
Types of Tables          		Description
================================        =========================================================================================================================================================================================================================================================================================================
Ordinary (heap-organized) table		This is the basic, general purpose type of table which is the primary subject of this chapter. Its data is stored as an unordered collection (heap)
Clustered table				A clustered table is a table that is part of a cluster. A cluster is a group of tables that share the same data blocks because they share common columns and are often used together.
Index-organized table			Unlike an ordinary (heap-organized) table, data for an index-organized table is stored in a B-tree index structure in a primary key sorted manner. Besides storing the primary key column values of an index-organized table row, each index entry in the B-tree stores the nonkey column values as well.
================================	=========================================================================================================================================================================================================================================================================================================

**This is Bold**