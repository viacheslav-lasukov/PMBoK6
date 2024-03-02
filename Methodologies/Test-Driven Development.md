---
aliases:
  - TDD
tags:
  - xp
---
## Cycle
| Step | Description |
| ---- | ---- |
| 1. Create a list of tests for the new feature | Given a system & a desired change in behavior, is to list all the expected variants in the new behavior. “There’s the basic case & then what if this service times out & what if the key isn’t in the database yet &…” The developer can discover these specifications by asking about [[use case]]s and [[User Story\|User Stories]]. A key benefit of test-driven development is that it makes the developer focus on requirements _before_ writing code. This is in contrast with the usual practice, where unit tests are only written _after_ code. |
| 2. Add one test from the list | Write an automated test that passes if the variant in the new behavior is met. |
| 3. Run all tests. The new test _should fail_ for expected reasons | This shows that new code is actually needed for the desired feature. It validates that the is working correctly. It rules out the possibility that the new test is flawed and will always pass. |
| 4. Write the simplest code that passes the new test | Inelegant or hard code is acceptable, as long as it passes the test. The code will be honed anyway in Step 6. No code should be added beyond the tested functionality. |
| 5. All tests should now pass | If any fail, the new code must be revised until they pass. This ensures the new code meets the test [[requirement]]s and does not break existing [[Base/Feature]]s. |
| 6. Refactor as needed, using tests after each refactor to ensure that functionality is preserved | Code is refactored for readability and maintainability. In particular, hard-coded test data should be removed. Running the test suite after each refactor helps ensure that no existing functionality is broken.<br><br>Examples of refactoring:<br>- moving code to where it most logically belongs<br>- removing duplicate code<br>- making names self-documening<br>- splitting methods into smaller pieces<br>- re-arranging [[inheritance]] hierarchies |
| 7. Add the next test on the list | Repeat the process with each test on the list until all tests are implemented and passing. |
| Repeat |  cycle above is repeated for each new piece of functionality. Tests should be small and incremental, and commits made often. That way, if new code fails some tests, the programmer can simply undo or revert rather than debug, it is important not to write tests that are so small as to effectively test merely the library itself unless there is some reason to believe that the library is buggy or not feature-rich enough to serve all the needs of the software under development. |
