Analyzing Resume fields to carve out Ranking of the University attended

**Project Description:**

The project involves working with extracted university / college names from multiple resumes and compare that with a list of standard university ranking list to grade and arrange resumes by university ranking order.

**Project Objective:**

The goal is to canonicalize school names in each dataset and merge them together to get the ranking of the school the applicant attended.

**Project Challenges:**

The schools are parsed from resume text, and as such, show a high variance in how people write. For example: The University of Texas at Austin, University of Texas - Austin, university of texas austin all correspond to the same university.

In the resume dataset, there are often schools with one to many match. For example, University of California appears often in the resume dataset, but rankings dataset only contains schools with locations (if there are multiple) such as University of California, Berkeley, University of California, Los Angeles, etc.
In such cases, need to obtain the median rank of all the universities that match.

