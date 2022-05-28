# CorssRefTest.java

## Food for thought
- it no so clear for us, the code-reviewers, why inheratence needs to be checked so extensivly
- all test are based on Inheritance and compare different subtypes
- there are a lot of tests, that doesn't check CrossRef functionality
- the test suite only tests BibEntry functionality
- For some test it is questinable if the enumaration of the complete samplespace is necessary to test the Inheritance

## Test 1 - forbiddenFields
- if this test is not useful for "sanity" checking this test is not in the right test suite
- else move the test to the BibEntryTest suite

## Test 2 - authorInheritance
- some comments would be appreciated or the test name should reveal more about the test's purpose
- two assertions are good in this case, because the whole test is cohesive

## Test 3 - mainTitleInheritance
- same comments as for test 2
- the test is very readable and easy to understand, thanks to the Fields/Object nameing

## Test 4 - bookTitleInheritance
- very similar to test 3
- the intention is clear

# Test 5 - journalTitleInheritance
- same commentary as before

# Test 6 - noTitleInheritance
- same commentary as before

# Test 7 - sameNameInheritance
- same commentary as before
- stream component is very large (Cartensian product of Type x Type x Entry)
