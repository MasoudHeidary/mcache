# mcache
A Python caching library with memory and disk support, customizable size, and multiple replacement policies (FIFO, FILO, Random, LFU).
mcache is a Python library designed for efficient caching with support for both in-memory and on-disk caching. Whether you need a quick, lightweight cache for your application or a persistent storage solution, mcache has you covered.

## Features
- Memory and Disk Caching: Choose between fast memory-based caching or persistent on-disk storage.
- Customizable Cache Size: Define the maximum size of your cache to suit your needs.
- Flexible Replacement Policies:
- - First-In-First-Out (FIFO)
- - First-In-Last-Out (FILO)
- - Random Replacement
- - Least Frequently Used (LFU): Removes the least-used entries first.
- Easy Integration: Simple API for seamless integration into your Python applications.

## Use Cases
- Web applications for caching responses or data
Machine learning workflows to store intermediate computations
- File system caching for improved performance
General-purpose data caching for any Python application