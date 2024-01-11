# python-concurrency
Concurrency in Python

## We will learn about:
- ThreadPools: multiple threads, same GIL (can only use 1 core)
- Multiprocessing: multiprocess, each process has its own GIL (can use multiple cores)
- Asyncio: single thread, single GIL (can only use 1 core). Can be used for IO bound tasks (network, disk, etc) but not CPU bound tasks (math, etc)
