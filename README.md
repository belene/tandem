###**TANDEM**: A Taxonomy and a Dataset of Real-World Performance Bugs###
[Link to TANDEM] (https://github.com/belene/tandem.git)

TANDEM is a collection of fully documented real-world performance bugs. To facilitate the comprehension of the set of performance bugs extracted in a systematic review of research papers, we bound together all the information into a single document of 67 pages called TAxoNomy  and  Dataset  of  pErforMance  bugs  (TANDEM). This document consists of a form for each of the 125 bugs identified in the search, containing the following information:

*Bug identifier. Each performance bug in the dataset has been assigned an identifier which consists of the initials of ?Performance Bug? (i.e., PB) plus a number. For example, PB1, PB2...PB125.

*Publication identifier. The publication doi where the bug was reported is included for the convenience of the reader.

*Year of publication. The year when the bug was described in the publication is also reported.

*Figure in the publication. For the sake of completeness, the name of the figure where the bug appeared within the publication is given (or alternatively, the listing or section).

*Taxonomy of the performance bug. The dataset also records the classification of the bugs according to the following taxonomy proposed:
    * Effect. This category refers to the non-functional properties affected when the bug manifested (time, memory or energy).
    * Cause. This block indicates the reasons that caused the appearance of the bug (structural aspects of the source code, derived from misunderstandings and misuse, originated by a missing operation, caused by a redundant action, etc.).
    * Context. This category aims to classify the bug depending on the kind of system where the bug was contained and its specificity. We also marked the programming language used to code the programs where the performance bug were found.

*Description of bug. A detailed description or pattern of the issue is provided.

*Source code. To complement the description of the bug, we also supply the fragment with the buggy source code.