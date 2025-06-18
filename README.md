[![Actions Status](https://github.com/Raku-L10N/DE/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/DE/actions) [![Actions Status](https://github.com/Raku-L10N/DE/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/DE/actions) [![Actions Status](https://github.com/Raku-L10N/DE/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/DE/actions)

NAME
====

L10N::DE - German localization of Raku

SYNOPSIS
========

    $ deuku -e 'sag "Hallo Welt"'
    Hallo Welt

```raku
use L10N::DE;
sag "Hallo Welt";
```

DESCRIPTION
===========

The `L10N::DE` distribution contains the logic to provide a German localization of the Raku Programming Language. It installs a `deuku` executable that will automatically activate the German localization. And it allows one to use the German localization in selected programs with a `use L10N::DE` statement.

AUTHORS
=======

Elizabeth Mattijsen <liz@raku.rocks>

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

