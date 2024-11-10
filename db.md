# Normalization:

- 1NF:
  - Each record has a unique primary key 
  - Each table cell contains a single value
- 2NF:
  - Non-key attributes are fully functionally dependent on the primary key.
- 3NF:
   - Non-key attributes depend only on the primary key, not on other non-key attributes (eliminate transitive dependencies Key -> Attr1 -> Attr2 )
- BCNF (Boyce-Codd Normal Form):
	Every determinant must be a candidate key.
- 4NF:
	No table has more than one independent multi-valued dependency.
- 5NF:
	Tables should be free from join dependencies and any form of redundancy

https://www.youtube.com/watch?v=GFQaEYEc8_8	

![img.png](img.png)
![img_1.png](img_1.png)

	every non-key attribute is fully dependent on the primary key
3NF + BCNF	no transitive dependencies.
BCNF	If a table is in 3NF and every non-prime attribute fully dependent on the candidate keys, then it is in BCNF.
4NF	If a table is in BCNF and has no multi-valued dependencies, it is in 4NF.

# ACID


# CAP


