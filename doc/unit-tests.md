Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the flatearthd tests manually, launch `src/test/test_flatearth`.

To add more flatearthd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the flatearth-qt tests manually, launch `src/qt/test/test_flatearth-qt`

To add more flatearth-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
