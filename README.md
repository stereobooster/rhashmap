# RHashMap

Idea: implement Reactive Hash Table for Rust.

I plan to start by porting [C implementation](https://github.com/torvalds/linux/blob/master/lib/rhashtable.c)

## Resources

 - [Std::HashMap](https://doc.rust-lang.org/beta/src/std/up/src/libstd/collections/hash/map.rs.html)
 - [Original paper](https://www.usenix.org/event/atc11/tech/final_files/Triplett.pdf)
 - [Relativistic hash tables, part 2: Implementation](https://lwn.net/Articles/612100/)
 - [What is RCU, Fundamentally?](https://lwn.net/Articles/262464/)
 - [Lock-freedom without garbage collection](https://aturon.github.io/blog/2015/08/27/epoch/)
 - [Crossbeam](https://github.com/aturon/crossbeam)
 - https://github.com/aturon/crossbeam/issues/13
