[![CI-macOS](https://github.com/evgeniyd/heapster-swift/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/evgeniyd/heapster-swift/actions/workflows/CI.yml)

# Heapster

[MaxHeap.swift](Heapster/MaxHeap.swift)

[MinHeap.swift](Heapster/MinHeap.swift)

The [Documentation](Heapster/Heapster.docc/Heapster.md) with more info.

<p align="left" width="30%">
    <img width="50%" src="/github-image.png">
</p>

# Problem

**Heap** is the data structure that I often has to drop into my [Leetcode](https://leetcode.com) solutions. I implemented `MinHeap` and `MaxHeap` for educational purpose from scratch once, and started using it for Leetcode problems. This project exists so one can quickly copy-and-paste a Heap to a [Swift] Leetcode solutions.

# Goals

1. Simple AF
2. Tested
3. Minificated (Less lines of code)
4. Performant enough

# Notes:

* Code is duplicated on purpose: the idea is one uses either [MaxHeap](Heapster/MaxHeap.swift) or [MinHeap](Heapster/MinHeap.swift) by copying and pasting the source code into Leetcode code editor.
* API of both Heaps is unified, except `extractMin()` vs. `extractMax()` to be more descriptive. It is a personal choice.
* I am toying with this idea of minifying the source code, and creating a release versions of it. Similar to how minification is often done with JavaScript. In the end of the day, for the goals of this project, the code should not be readable as far as it delivers expected behavior.

# TODO

- [x] Add test to `MinHeap`
- [x] Add tests to `MaxHeap`
- [ ] Script to minify `MinHeap`
- [ ] Script to minify `MaxHeap`
- [ ] Move code comments to the documentation
- [ ] Add performance tests

# Leetcode
Problems that *can* be solved with `Heap` data structure.

* [1481. Least Number of Unique Integers after K Removals](https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/) | [Solution](https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/solutions/4749396/heap-solution/)
* [1642. Furthest Building You Can Reach](https://leetcode.com/problems/furthest-building-you-can-reach/) | [Solution](https://leetcode.com/problems/furthest-building-you-can-reach/solutions/4749423/minheap-solution/)
* [2402. Meeting Rooms III](https://leetcode.com/problems/meeting-rooms-iii/) | [Solution](https://leetcode.com/problems/meeting-rooms-iii/solutions/4748798/2-solutions-linear-search-two-heaps/)
* [2092. Find All People With Secret](https://leetcode.com/problems/find-all-people-with-secret/) | [Solution](https://leetcode.com/problems/find-all-people-with-secret/solutions/4778215/minheap-solution)
* [716. Max Stack](https://leetcode.com/problems/max-stack/) | [Solution](https://leetcode.com/problems/max-stack/solutions/4856115/heap-stack-set-comparable-node)
* [253. Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) | [Solution](https://leetcode.com/problems/meeting-rooms-ii/solutions/4934650/heaps-solutions-1-heap-2-heaps/)
* [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/description/) | [Solution](https://leetcode.com/problems/top-k-frequent-elements/solutions/4939645/maxheap-with-comparable-struct)
