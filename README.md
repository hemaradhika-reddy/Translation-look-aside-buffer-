# Translation-look-aside-buffer-
This system optimizes memory access by storing frequently accessed page table entries in a high-speed cache known as the TLB. By doing so, it reduces the need for repeated main memory references, enhancing overall performance. However, due to limited register size, the entire page table remains in main memory, necessitating two main memory references for address resolution. The TLB mitigates this issue by storing and providing rapid access to recent translations, thus improving memory access efficiency.



