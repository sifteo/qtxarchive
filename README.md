# QtxArchive

QtxArchive provides classes for handling archive formats, including zip and tar.

## Tests

To run the test suite, first configure and build QtxArchive as a dynamic
library, which each test executable will link against.  Then invoke the `check`
target to execute all tests in the suite.

    $ qmake CONFIG+=dylib
    $ make
    $ make check

## License

[Apache License, Version 2.0](http://opensource.org/licenses/Apache-2.0)

Copyright (c) 2012-2013 Sifteo Inc. <[http://www.sifteo.com/](http://www.sifteo.com/)>