# Examples for the custom mutator

These are example and helper files for the custom mutator feature.
See [docs/custom_mutators.md](../docs/custom_mutators.md) for more information

Note that if you compile with python3.7 you must use python3 scripts, and if
you use pyton2.7 to compile python2 scripts!

example.c - this is a simple example written in C and should be compiled to a
          shared library. Use make to compile it and produce libexamplemutator.so

example.py - this is the template you can use, the functions are there but they
           are empty

simple-chunk-replace.py - this is a simple example where chunks are replaced

common.py - this can be used for common functions and helpers.
          the examples do not use this though. But you can :)

wrapper_afl_min.py - mutation of XML documents, loads XmlMutatorMin.py

XmlMutatorMin.py - module for XML mutation
