# Largest-Prime-Factor-
This project is a Java implementation for computing the largest prime factor of an input number.
It combines straightforward mathematics with practical performance tricks:

Algorithm: iterative factor stripping (remove 2s, then odd factors up to √n) to isolate the largest prime factor.

Performance: early exits when the residual becomes prime; skips non-viable candidates; optional multithreaded factor scanning for big inputs.

Structure: modular packages for the CLI, core factoring engine, and helpers; built with Gradle; tested with JUnit.

Usage: run from the command line with an integer or from a library API method (e.g., LargestPrimeFactor.of(long n)), returning the largest prime factor or n itself if n is prime.

Why it matters: showcases algorithmic thinking, complexity analysis (≈ O(√n) in the worst case, much less in practice), and production-style Java project setup (tests, build, and documentation).
