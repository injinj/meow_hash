# Meow hash 0.4/aesdecx2
This is based on the
[0.4/himalayan](https://github.com/cmuratori/meow_hash/tree/v0.4) of Meow hash.  It is modified to use
2 rounds of AESDEC instead of one.  This causes it to pass the LongNeighbors
test in [smhasher](https://github.com/hmakholm/smhasher) from Hening Makholm.

I also modified the hashes to use a 128 bit seed instead of a 64 bit seed.

# Meow hash 0.4/himalayan
This is the official x64 implementation of the Meow hash, an extremely fast non-cryptographic hash.  See https://mollyrocket.com/meowhash for usage, implementation, and license details.

This version is v0.4 and is EXPERIMENTAL.  It is only designed for testing and comment right now.  Updates will be coming which finalize the hash function, but for right now it is still considered in flux.  This version builds on Windows/MSVC, Linux/CLANG, and Mac/CLANG, and supports x64 and ARM processors with AES instructions and (much slower) vanilla C for compatibility.
