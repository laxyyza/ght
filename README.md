# GHT - Generic Hash Table
Simple Hash Table in C
### Features
 *  Dynamic sizing based on load factor, with adjustable max & min thresholds.
 *  Thread-Safe.
 *  Automatic memory management (if `ght_t::free` is provided).
 *  Generic Types.

# Build
> Setup
```
meson setup build/
```
> Compile
```
ninja -C build/
```
> Run
```
./build/example
```
# Next
Binary Search Tree / Red-Black Tree
