# Computer-Architecture
## Server Demo
Host: nthucad.cs.nthu.edu.tw  
port: 22  
no permission now

## Description
I tried to simulate Cache policy of LRU(least recently used) replacement.  
I seperately produced the code based on LSB(least significant bits, without offset bits) indexing scheme and the indexing scheme which I designed to minimalize cache miss count.

### Data structure
* Use **string ref_list[10001]** to store the reference sequence. 
*s