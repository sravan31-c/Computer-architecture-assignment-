# Computer-architecture-assignment-
Assignment-LRU CACHE MEMORY REPLACEMENT ALGORITHM AND EAT USING TLV
LRU Cache Replacement Algorithm

Aim

To write a Python program to simulate the Least Recently Used (LRU) cache replacement algorithm.

Description

LRU (Least Recently Used) is a cache replacement algorithm that removes the block that has not been used for the longest time when the cache becomes full.

Assumptions

- Cache capacity is 3 memory blocks.
- Initially, the cache is empty.
- Access sequence: 4, 2, 1, 4, 3, 2, 5, 4.

Working

1. Check whether the requested block is present in the cache.
2. If present, it is a HIT.
3. If absent, it is a MISS.
4. If the cache is full, remove the least recently used block.
5. Insert the new block into the cache.
6. Calculate total hits, misses and hit ratio.

Output

- Total Hits: 1
- Total Misses: 7
- Hit Ratio: 0.125

Conclusion

The LRU cache replacement algorithm was successfully implemented using Python. It replaces the least recently used memory block when the cache is full.
