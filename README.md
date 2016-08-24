Apache Hadoop Configuration 
===========================

Apache-Hadoop-Config 
--------------------

This module provides a configuration for an instance of Apache Hadoop
using inputs either from the supplied arguments or probing the system,
on which it is installed, allowing the instance to be optimized
for a specific system configuration. This module writes Apache Hadoop
configuration XML files, as needed, enabling rapid building of Hadoop
clusters on a set of hardware.

Presently, it comes with standard (trivial) filesystem settings and 
optimized memory settings for Apache Hadoop configuration.


Requirements:
-------------

This module assumes that Apache Hadoop (or any version, though not tested)
has just been installed and configuration directory is writable. Apache
Hadoop configuration directory will be either supplied through command-line
or through SHELL variable or assumed to be in default path such as
/usr/local/hadoop/etc/hadoop.


Installation:
-------------

To install this module type the following:

```
   perl Makefile.PL
   make
   make test
   make install
```

Documentation:
--------------

After the installation, the documentation for this module can be 
found using perldoc command:
```
    perldoc Apache::Hadoop::Config
```
or, by using Linux man page:
```
    man Apache::Hadoop::Config
```

Copyright and Licence:
----------------------

Copyright (C) 2015 by Snehasis Sinha

This library is free software; you can redistribute it and/or modify
it under the same terms as Apache Licence 2.0
