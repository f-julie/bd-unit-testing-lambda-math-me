# The `AtaMathTest`

## What's `average()` trying to do?

We've added a new method to the `AtaMath` class and would like you to ensure it's properly tested. Through manual
testing we think we've verified that everything works, but we all know that unit tests are much more efficient
and reliable!

Open up the `AtaMath` class in this package.

Look at the `average()` method, and answer for yourself:
* What does the method do?
* What are some test cases that are relevant for this method?

## Write the tests!

Let's write some JUnit unit tests from the test cases provided at
`tst/com/amazon/ata/unittesting/math/test_cases.md`.

### Write your first test

Let's make this one the single integer test (first test case in the `test_cases.md` file)

Be prepared to share something you learned from creating this test...or what were the fixes you had to make from
your first attempt at it.

### Write the remaining "Minimum cases"

Make sure your tests pass. If they do not, diagnose and see what's wrong. It's *probably* the test code (which is a
fairly common occurrence when you're writing new code/test code), so check there first.

Push your code once you are satisfied. You can run `./gradlew -q clean :test` to run all tests. 
Or you can run them from within IntelliJ directly.

Once you've pushed, find your snippets package on code.amazon.com, click on the "Commits" tab, then click
on your commit that shows the changes you've made.

### Extension

If you have time, go ahead and move on to the "Extension cases". Create another test you can think of that might
add to make the test suite even more complete.
