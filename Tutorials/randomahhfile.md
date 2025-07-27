Arithmetic, load/store and branch instructions for a processor has 
CPI of 1, 12 and 5 respectively. On a single process, a program requires
the execution of 2.56*10^9 arithmetic instructions, 1.28 *10^9 load/store 
instructions and 0.256 * 10^9 branch instructions. The processor has a
2 GHz clock frequency.

Assume that, as the program is parallelized to run over multiple cores, the 
number of arithmetic and load/store instructions per processor is divided by
0.7p (where p is the number of processors) but the number of branch instructions
per processor remains the same.

a) Find the total execution time for this program on 1, 2, 4 and 8 processors. Shows
the relative speedup of the 2,4 and 8 processor result relative to the single processor
result.

| P | Arithmetic  | L/S         | Branch      | Cycles | Exec Time | Speed up |
|---|-------------|-------------|-------------|--------|-----------|----------|
| 1 | 2.56 * 10^9 | 1.28 * 10^9 | 2.56 * 10^8 |        |           |          |
| 2 | 1.83 * 10^9 | 9.14 * 10^8 | 2.56 * 10^8 |        |           |          |
| 4 | 9.14 * 10^8 | 4.57 * 10^8 | 2.56 * 10^8 |        |           |          |
| 8 | 4.57 * 10^8 | 2.29 * 10^8 | 2.56 * 10^8 |        |           |          |
