# CMPS 2200 Recitation 6
## Answers

**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |     1340 | 826 | 0.61641791 |      
alice29.txt    | 1039367 | 676374 | 0.65075570  |
asyoulik.txt    |876253 | 606448 | 0.69209235 |
grammar.lsp    | 26047 | 17356 | 0.66633393  |
fields.c    | 78050 | 56206 | 0.72012812 |


Therefore a trend that we notice is that the Huffman cost was always less than the fixed length cost , this is because the Huffman coding uses a far superior algorithm in order to reduce total time when compared to the Fixed Length Coding.

- **e.**


Looking at the data , I was able to realize that if each character is given the same frequency, the expected cost of the Huffman coding would be the same throughout the document. In doing so, the cost can be predicted to be nlog(n) with n being the number of leaves.
