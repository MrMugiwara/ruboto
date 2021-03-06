Contributing
============

Want to contribute? Great! Meet us in #ruboto on irc.freenode.net, fork the
project and start coding!

"But I don't understand it well enough to contribute by forking the project!"
That's fine. Equally helpful:

* Use Ruboto and tell us how it could be better.
  Report [issues](http://github.com/ruboto/ruboto/issues).
* Browse http://ruboto.org/ and the documentation, and let us know how to make
  it better.
* As you gain wisdom, contribute it to
  [the wiki](http://github.com/ruboto/ruboto/wiki).
* When you gain enough wisdom, reconsider whether you could fork the project.

If contributing code to the project, please run the existing tests and add tests
for your changes.  You run the tests using rake:

    $ rake test

We have set up a matrix test that tests multiple configuations on the emulator:

    $ ./matrix_tests.sh

All branches and pull requests on GitHub are also tested on
[https://travis-ci.org/ruboto/ruboto](https://travis-ci.org/ruboto/ruboto).
