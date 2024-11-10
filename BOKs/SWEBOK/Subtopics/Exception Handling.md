---
tags:
  - swebok/subtopic
SWEBOK_Topic: "[[Construction Technologies]]"
---
Exceptions are used to detect and process errors or exceptional events.

The basic structure of an exception is that a routine uses throw to throw a detected exception and an exception handling block will catch the exception in a try-catch block.

The try-catch block may process the erroneous condition in the routine or it may return control to the calling routine.

Exception handling policies should be carefully designed following common principles:
- including in the exception message all information that led to the exception
- avoiding empty catch blocks
- knowing the exceptions the library code throws
- building a centralized exception reporter
- standardizing the program’s use of exceptions