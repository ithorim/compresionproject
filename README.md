# Data Compression and Error Correction Coding Project

This project consists of two parts: p1 and p2, focusing on data compression algorithms and error correction coding, respectively.

## Part 1 (p1): Data Compression Algorithms

In this part, we implemented and analyzed four different data compression algorithms:

1. Shannon-Fano Coding
2. Huffman Coding
3. LZ77 (Lempel-Ziv 77)
4. LZW (Lempel-Ziv-Welch)

For each algorithm, we:
- Implemented the encoding and decoding processes
- Applied the compression to binary input files
- Calculated and compared compression ratios

Key implementations:
- Entropy calculation for input files
- Construction of prefix-free codes (Shannon-Fano and Huffman)
- Sliding window approach for LZ77
- Dictionary-based compression for LZW

The performance of each algorithm was evaluated based on compression ratio and execution time.

## Part 2 (p2): Error Correction Coding

This part focuses on Low-Density Parity-Check (LDPC) codes and their decoding algorithms. The main components include:

1. LDPC Matrix Generation
   - Created a sparse parity-check matrix H using a structured random approach

2. Syndrome Table and Code Distance
   - Generated a syndrome table for efficient decoding
   - Calculated the code distance to determine error-correcting capabilities

3. Gallager B Algorithm Implementation
   - Implemented the Gallager B hard-decision decoding algorithm
   - Analyzed its performance by finding the least weight error pattern it fails to correct

Key aspects:
- Use of numpy for efficient matrix operations
- Implementation of iterative decoding processes
- Analysis of code performance and limitations

Both parts demonstrate practical applications of information theory and coding techniques in data compression and error correction.