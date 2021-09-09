[![Actions Status](https://github.com/lizmat/Tie-Array/workflows/test/badge.svg)](https://github.com/lizmat/Tie-Array/actions)

NAME
====

Raku port of Perl's Tie::Array module

SYNOPSIS
========

    use P5tie;
    use Tie::Array;

DESCRIPTION
===========

This module tries to mimic the behaviour of Perl's `Tie::Array` module as closely as possible in the Raku Programming Language.

Tie::Array is a module intended to be subclassed by classes using the </P5tie|tie()> interface. It depends on the implementation of methods `FETCH`, `STORE`, `FETCHSIZE` and `STORESIZE`.

The `EXISTS` method should be implemented if `exists` functionality is needed. The `DELETE` method should be implemented if `delete` functionality is needed. Apart from these, all other interfaces methods are provided in terms of `FETCH`, `STORE`, `FETCHSIZE` and `STORESIZE`.

SEE ALSO
========

[P5tie](P5tie), [Tie::StdArray](Tie::StdArray)

AUTHOR
======

Elizabeth Mattijsen <liz@raku.rocks>

Source can be located at: https://github.com/lizmat/Tie-Array . Comments and Pull Requests are welcome.

COPYRIGHT AND LICENSE
=====================

Copyright 2018, 2019, 2020, 2021 Elizabeth Mattijsen

Re-imagined from Perl as part of the CPAN Butterfly Plan.

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

