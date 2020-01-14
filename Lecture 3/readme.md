* Paging (read about it)
  * Allows virtual address to map to physical address.
* Buses
* Caches
  * Read is simple.
  * When we do write; if that memory block is being used by multiple processes; we need to handle it. (coherence)
  * Handled at software and hardware level (?)
* Cost of compute vs cost of communication (between threads/processes etc).
* Creating thread has its own cost. Use threads if it does significant work to justify its cost
* Cache Coherence
  * Cache Coherence Protocols (CCP) implemented at microprocessor level
  * GPU have different memory model. Don't need to have have CCP.
