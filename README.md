# OLAC-Type-Values
Small examples of OALC Records


## RPaterson-Static-Repo

The `RPaterson-Static-Repo.xml` repo is a validating repo. It was converted to JSON in `RPaterson-Static-Repo.json`. However this conversion of JSON does not preserve the necessary types (literals/nonliterals). It also doesn't preserve the attribute based distinctions such as can be [seen in line 97](https://github.com/HughP/OLAC-Type-Values/blob/2b9e8b951e0a9faa496fa1b498234e8ce3838cb9/RPaterson-Static-Repo.json#L97) where DCMIType and OLAC type refinements are lost for their specificty. 
