This repository contains a demonstration of a common error in COBOL programs: array index out-of-bounds errors.  The `bug.cob` file shows the erroneous code, while `bugSolution.cob` presents the corrected version. The bug arises from a lack of robust error checking when using OCCURS clauses and indexes.  Always ensure your index remains within the defined bounds of your table.  The solution introduces a check to prevent the error.