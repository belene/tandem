# **TANDEM**: A Taxonomy and a Dataset of Real-World Performance Bugs
[Link to TANDEM](https://github.com/belene/tandem/blob/master/docs/TANDEM.pdf)

## INTRODUCTION 
TANDEM is a taxonomy and a dataset for real-world performance bugs. TANDEM is elaborated according to a systematic review of the related literature that allowed us to extract exhaustive information of the exposed performance bugs. The proposed taxonomy classify the bugs in three main categories: effects,  causes  and  contexts  of performance bugs. In turn, these main blocks are divided into subcategories to enable the accurate classification of bugs and to ease its comprehension. Additionally, we provide a dataset composed of 125 real-world performance issues fully documented including the buggy source code and the categorization of all the bugs based on the proposed taxonomy. This is expected to facilitate both the distribution and the reusability of performance bugs among researchers.

### TANDEM DATASET
TANDEM dataset is a collection of fully documented real-world performance bugs. To facilitate the comprehension of the set of performance bugs extracted in a systematic review of research papers, we bound together all the information into a single document of 67 pages. This document consists of a form for each of the 125 bugs identified in the search, containing the following information:
* ***Bug identifier***. Each performance bug in the dataset has been assigned an identifier which consists of the initials of "Performance Bug" (i.e., PB) plus a number. For example, PB1, PB2...PB125.
* ***Publication identifier***. The publication *doi* where the bug was reported is included for the convenience of the reader.
* ***Year of publication***. The year when the bug was described in the publication is also reported.
* ***Figure in the publication***. For the sake of completeness, the name of the figure where the bug appeared within the publication is given (or alternatively, the listing or section).
* ***Taxonomy of the performance bug***. The dataset also records the classification of the bugs according to the TANDEM taxonomy proposed (more details in the section TANDEM Taxonomy).
* ***Description of bug***. A detailed description or pattern of the issue is provided.
* ***Source code***. To complement the description of the bug, we also supply the fragment with the buggy source code.

The performance bugs in TANDEM dataset are alphabetically ordered by effect, cause, context, language, year of the publication and, for performance bugs referenced in the same publication, number of the figure or listing in the paper. 

### TANDEM TAXONOMY
TANDEM taxonomy is a complete classification of the types of real-world performance issues we have found in the related literature. Specifically, we classify the performance bugs according to three main categories described below: 

|Category | Description |
| ----- |-------------|
|Effect |The effect that the bug produces in the application. Three are the classical non-functional properties impacted by the introduction of performance bugs: time, memory and energy.|
|Cause | The cause that originated the bug. We classify the bugs' causes into five secondary categories: structural aspects, misunderstandings and misuse, missing operation, redundant action, and others to cover those cases not fitting in  the  above  categories.|
|Context | The context where the bug appeared. We classify the bugs' contexts into three secondary aspects: project type, general-practice and language-specific.|
