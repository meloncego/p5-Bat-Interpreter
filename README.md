# NAME

Bat::Interpreter - Pure perl interpreter for a small subset of bat/cmd files

# VERSION

version 0.024

# SYNOPSIS

```perl
#!/usr/bin/env perl -w

use 5.014;
use Bat::Interpreter;

my $interpreter = Bat::Interpreter->new;

$interpreter->run('basic.cmd');

say join("\n", @{$interpreter->executor->commands_executed});
```

# DESCRIPTION

Pure perl interpreter for a small subset of bat/cmd files.

[![Build status](https://ci.appveyor.com/api/projects/status/xi8e6fjjxwfp77th/branch/master?svg=true)](https://ci.appveyor.com/project/pablrod/p5-bat-interpreter/branch/master)

# METHODS

## run

Run the interpreter

# BUGS

Please report any bugs or feature requests via github: [https://github.com/pablrod/p5-Bat-Interpreter/issues](https://github.com/pablrod/p5-Bat-Interpreter/issues)

# AUTHOR

Pablo Rodríguez González <pablo.rodriguez.gonzalez@gmail.com>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2020 by Pablo Rodríguez González.

This is free software, licensed under:

```
The MIT (X11) License
```

# CONTRIBUTORS

- eva.dominguez <eva.dominguez@meteologica.com>
- Eva <meloncego@gmail.com>
- juanradiego <kilaweo@gmail.com>
- Nicolas De los Santos <ndls05@gmail.com>
- pablo.rodriguez <pablo.rodriguez@meteologica.com>
- ricardo.gomez <ricardogomezescalante@gmail.com>
- Toby Inkster <tobyink@cpan.org>
