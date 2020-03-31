# **TANDEM**: A Taxonomy and a Dataset of Real-World Performance Bugs
[Link to TANDEM](https://github.com/belene/tandem/blob/master/docs/TANDEM.pdf)

## INTRODUCTION 
TANDEM is a taxonomy and a dataset for real-world performance bugs. TANDEM is elaborated according to a systematic review of the related literature that allowed us to extract exhaustive information of the exposed performance bugs. The proposed taxonomy classify the bugs in three main categories: effects,  causes  and  contexts  of performance bugs. In turn, these main blocks are divided into subcategories to enable the accurate classification of bugs and to ease its comprehension. Additionally, we provide a dataset composed of 125 real-world performance issues fully documented including the buggy source code and the categorization of all the bugs based on the proposed taxonomy. This is expected to facilitate both the distribution and the reusability of performance bugs among researchers.

### TANDEM DATASET
TANDEM dataset is a collection of fully documented real-world performance bugs. To facilitate the comprehension of the set of performance bugs extracted in a systematic review of research papers, we bound together all the information into a single document of 67 pages. This document consists of a form for each of the 125 bugs identified in the search, containing the following information:
* *Bug identifier*. Each performance bug in the dataset has been assigned an identifier which consists of the initials of ?Performance Bug? (i.e., PB) plus a number. For example, PB1, PB2...PB125.

* *Publication identifier*. The publication doi where the bug was reported is included for the convenience of the reader.

* *Year of publication*. The year when the bug was described in the publication is also reported.

* *Figure in the publication*. For the sake of completeness, the name of the figure where the bug appeared within the publication is given (or alternatively, the listing or section).

* *Taxonomy of the performance bug*. The dataset also records the classification of the bugs according to the following taxonomy proposed (detailed in the section TANDEM Taxonomy):
    * *Effect*. This category refers to the non-functional properties affected when the bug manifested (time, memory or energy).
    * *Cause*. This block indicates the reasons that caused the appearance of the bug (structural aspects of the source code, derived from misunderstandings and misuse, originated by a missing operation, caused by a redundant action, etc.).
    * *Context*. This category aims to classify the bug depending on the kind of system where the bug was contained and its specificity. We also marked the programming language used to code the programs where the performance bug were found.

* *Description of bug*. A detailed description or pattern of the issue is provided.

* *Source code*. To complement the description of the bug, we also supply the fragment with the buggy source code.

The performance bugs in TANDEM dataset are alphabetically ordered by effect, cause, context, language, year of the publication and, for performance bugs referenced in the samepublication, number of the figure or listing in the paper. 

### TANDEM TAXONOMY
TANDEM taxonomy is a complete classification of the types of real-world performance issues we have found in the related literature. Specifically, we classify the performance bugs according to three main categories: 1) the effect that the bug has on the application, 2) the cause that originated the bug, and 3) the context where the bug appeared.

#### EFFECTS
Three are the classical non-functional properties impacted by the introduction of performance bugs: time, memory and energy. Table below summaries the types of effects that performance issues can produce.

|Effect | Description |
| ----- |-------------|
|Energy |An excessive amount of energy is consumed because the implementation leads to leaks of energy|
|Execution time | A slowdown is perceived in the system, such as GUI lagging, low throughput or poor responsiveness|
|Memory | An inadequate use of the memory is observed, including memory churn (excessive generation of objects), memory bloat (storage of large amounts of unnecessaryinformation), or memory leaks|

#### CAUSES
We found a great diversity of root causes for the occurrence of performance problems in the analyzed primary studies. After a  thorough evaluation of each performance bug, we detected similar reasons behind the introduction of most of these bugs. As such, we could classify them into five secondary categories: performance bugs related to structural aspects of the source code, derived from misunderstandings and misuse, originated by a missing operation, caused by a redundant action, and others to cover those cases not fitting in  the  above  categories.  Those  five  categories  as  well  as their corresponding subcategories are described in the table below. We should note that some bugs can caused for a combination of reasons, being able to classify them in different categories at the same time.


