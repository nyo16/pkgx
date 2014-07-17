pkgx - Easy packaging of Erlang releases 
========================================

This program can be used to make OS packages for an Erlang application
bundled as an OTP release.

Getting started
---------------

Create a ``pkgx.config`` in the root of your project. Look at the
``pkgx.config.sample`` file for instpiration. Also, make sure that
you're all set with generating a release using the ``relx`` tool.

Typical workflow scenario:

    $> rebar compile
    $> relx release
    $> pkgx

Now, you have a `*.deb` file in your directory which holds the Erlang
release and can be easily installed on a target system.

