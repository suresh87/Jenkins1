Jenkins1

This package provides an implementation of the Jenkins96 hashing algorithm (by Robert John Jenkins Junior) for node.js
Disclaimer

    This was built to produce the same hashes used by World of Warcraft, may differ from spec.
    This does not perform fast. Do not use in important/time-sensitive environments.
    The code is not optimal at all; feel free to contribute improvements!

Dependancies

    ES6 Support (Node 6+)
    long - Used for computing the 64-bit output hash.
    int32 - Allows native int32 usage in Node for overflowing.

Installing

npm install jenkins1



