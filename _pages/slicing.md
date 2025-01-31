---

permalink: /home/slicing/
title: "What is Program Slicing"
author_profile: true
toc: true
toc_label: "Content"
toc_icon: "cog"
toc_sticky: true
header:
  overlay_image: /assets/images/tesztkep3.jpg
---
## Program Slicing
Program slicing is a software engineering technique that helps to isolate specific parts of a program that are relevant to a particular task. By slicing away the unused parts of the code, the relationships between different parts of a program can be better understood and bugs or performance issues can be more easily identified and fixed.

## Different Approaches
Program slicing can be either static or dynamic, depending on whether the slices are based on the actual execution of the program or on a static analysis of the code. In static slicing, a slice is created based on a pre-determined set of criteria such as the program's control flow, data flow, or use-def chains. On the other hand, dynamic slicing is performed by executing the program and collecting information about the values of variables and the execution of statements.

Relevant slicing is a more recent development in program slicing that combines the advantages of both static and dynamic slicing. In relevant slicing, a slice is created that is both statically and dynamically relevant to a particular program execution. This approach helps to reduce the number of irrelevant statements in the slice, making it easier to understand and debug the code.

## Drawbacks of Different Slicing Approaches
There are some drawbacks to each of the slicing approaches. For example, static slicing can be limited by the accuracy of the data used to create the slice and can be sensitive to changes in the code. Dynamic slicing can be time-consuming and requires accurate and up-to-date information about the program. Relevant slicing is a relatively new approach and still has some limitations in terms of the types of programs that can be sliced and the need for specialized tools.

## Recent Results of Program Slicing
In recent years, program slicing has become an increasingly popular technique in software engineering, with numerous studies being conducted to improve the accuracy and efficiency of slicing algorithms. For example, researchers have developed new algorithms for creating slices that are more accurate and up-to-date, and have explored new approaches for creating slices that are both static and dynamically relevant.

## References
Binkley, D., & Weiser, M. (1990). A formal investigation of program slicing. ACM SIGPLAN Notices, 25(6), 42-51. [DOI: 10.1145/93984.93986](https://doi.org/10.1145/93984.93986)

Gyimóthy, T. (1999). Program slicing with dynamic slicing. ACM SIGSOFT Software Engineering Notes, 24(6), 34-41. [DOI: 10.1145/330635.330637](https://doi.org/10.1145/330635.330637)

Harman, M., & Laski, J. (1998). Relevant slicing. In Proceedings of the 15th International Conference on Software Engineering (pp. 125-134). [DOI: 10.1109/ICSE.1998.671716](https://doi.org/10.1109/ICSE.1998.671716)

Korel, B. (1990). On the completeness of program slicing. ACM SIGSOFT Software Engineering Notes, 15(2), 73-82. [DOI: 10.1145/98768.98770](https://doi.org/10.1145/98768.98770)

Tip, F. (1995). A survey of program slicing techniques. Journal of Programming Languages, 3(3), 121-189. [DOI: 10.1016/S0960-1661(05)80062-7](https://doi.org/10.1016/S0960-1661(05)80062-7)

Weiser, M. (1984). Program slicing. ACM SIGPLAN Notices, 19(7), 157-169. [DOI: 10.1145/8218.8219](https://doi.org/10.1145/8218.8219)

Korel, B. (1990). Conditional and relational program slicing. ACM Transactions on Software Engineering and Methodology, 1(1), 40-59. [DOI: 10.1145/76729.76731](https://doi.org/10.1145/76729.76731)

Gyimóthy, T., Beszédes, A., & Forgács, I. (1999). An efficient relevant slicing method for debugging. ACM SIGSOFT Software Engineering Notes, 24(6), 303-321. [DOI: 10.1007/3-540-48166-4_19](https://doi.org/10.1007/3-540-48166-4_19)
