# Testing

* What is automated testing, and what is the difference from manual testing?
* What is unit-test?
* What is TDD?
* What is the advantage of TDD? Why write tests first and then code?
* What are regression bugs and how do automated tests help solve them?
* Why do side effects impair code testability?
* What is mock and when should they be used?
* What is a spy and when should they be used?
* Is it worth testing private class methods? Why?
* Why group separate tests inside unit tests?
* How long should an ideal work cycle last: _ writing a test -> changing functionality -> refactoring_?
* What libraries are there for creating tests and running them (and how do they differ from each other)?
* How do tests help newcomers enter the project?
* How do tests help in documenting a project?
* How do tests speed up getting feedback from the work done and why is this feedback important?
* What steps in manual testing help avoid unit tests?
* Why make tests run fast?
* How to ensure that test errors are as obvious as possible?
* Do I need to automatically test the tests themselves?
* What are the boundary conditions? Why test them?
* What is heisenbug? What are the ways to debug them?
* What is fixture?
* What is code coverage with tests? What tools are there for analyzing it?
* How are unit tests different from integration tests? Why is integration harder to write and maintain?
* Why pay attention to patterns when tests fail? How can analysis of which particular test combination fall off help?
* How do tests help in designing? Why is module testability an excellent indicator of "code cleanliness"?
* How do tests help with refactoring?
* What are the advantages of the rule of one concept per unit test?
* What are the advantages of tests isolated from each other?
* How to find a balance between the number of tests and code coverage? What problems can be caused by an excessive number of unit tests?
* What is a test pyramid? What role do tests play there? What role does static code analysis play there?
* Are types a complete replacement for unit tests? Why?
* What are end-to-end tests? What is the difference from integration?
* When do tests really slow down development, and when do they speed up?
* Are tests a full part of the system and code base?
* Why is testing becoming less convenient if you test not only public but also private methods?
* What are Test Double and Fake? What is the difference from Mock and Stub?
* What is the difference between testing with behavior verification and state verification?
* Why does the application of Mocks provoke behavior verification?
* What are Solitary and Sociable tests? What are the benefits of solitary tests? Are there any benefits to Sociable tests?
* Why does Mocks simplify outside-in design?
* Why strive to ensure that tests can be run as conveniently as possible and with just one team?
* Is it worth writing "training" integration tests that are run only manually and only for testing an external API (for example, the Web API Github)?

### Links

* [A quick guide to Manual Testing Vs Automated Testing](https://reqtest.com/testing-blog/manual-testing-vs-automated-testing/)
* [Зачем нужны юнит-тесты](https://tproger.ru/translations/unit-tests-purposes/)
* [Как, используя TDD, сократить время разработки](https://www.simbirsoft.com/blog/razrabotka-cherez-testirovanie-polza-i-vred/)
* [Об использовании модульных тестов и TDD](https://eax.me/unit-testing/)
* [Автоматические тесты при помощи chai и mocha](https://learn.javascript.ru/testing/)
* [Знакомство с фронтенд-тестированием. Часть первая. Введение](https://tproger.ru/translations/frontend-testing-1/)
* [Осторожно! Возможны побочные эффекты](http://blog.csssr.ru/2017/10/07/side-effects)
* [JS testing tools overview](https://medium.com/welldone-software/an-overview-of-javascript-testing-in-2019-264e19514d0a)
* Clean code. Part 9.
* [Гид по ручному тестированию приложений: преимущества, этапы и методологии](https://habr.com/ru/company/skillbox/blog/418889/)
* [Test first by R. Marting](https://blog.cleancoder.com/uncle-bob/2013/09/23/Test-first.html)
* [5 Questions Every Unit Test Must Answer by E. Elliott](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d)
* [Unit Tests, How to Write Testable Code and Why it Matters](https://www.toptal.com/qa/how-to-write-testable-code-and-why-it-matters)
* [UnitTest by M. Fowler](https://martinfowler.com/bliki/UnitTest.html)
* [Unit Tests from XP](http://www.extremeprogramming.org/rules/unittests.html)
* [Test Reviews Vs. Code Reviews - Some Helpful Tips](https://osherove.com/blog/2007/3/13/test-reviews-vs-code-reviews-some-helpful-tips.html)
* [Types and Tests](https://blog.cleancoder.com/uncle-bob/2017/01/13/TypesAndTests.html)
* [Mocks Aren't Stubs](https://www.martinfowler.com/articles/mocksArentStubs.html)
* [We don't write tests. There just isn't time for luxuries.](https://www.jamesgolick.com/2007/8/22/we-dont-write-tests-there-just-isnt-time-for-luxuries.html)
* [Юнит-тестирование для чайников](https://habr.com/en/post/169381/)
