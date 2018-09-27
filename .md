# Assignment-5

Part 1: (10 points)
Proove each of the following. Indicate which proof method you are using and show your work.

 Show that the square root of 2 is irrational.
 
 sqrt(2) = a / b
 2 = a^2 / b^2
 2(b^2) = a^2
 a is an even number bc its square is even, so a = 2k.
 2 = (2k)^2 / b^2
 2 = 4k^2 / b^2
 2b^2 = 4k^2
 2b^2 = 2(2k^2)
 b^2 = 2k^2
 b = 2k
 be = an even number
 due a and b both being proven even, it's a contradiction because they are supposed to be in their most simplified form
 
 -Contradiction
 _______________________________________________
 If n = 25, 100, or 169, then n is a perfect square and is the sum of two perfect squares.
 
 n = m^2 = k^2 + p^2.
 
 n = 25 = 5^2 = 3^2 + 4^2.
 n = 100 = 6^2 + 8^2.
 n = 169 = 13^2 = 12^2 + 5^2.
 -Exhaustion.
 _______________________________________________________________
 The sum of two odd integers is even. Hint: By definition, even integers can be expressed as 2n,
 thus odd integers can be expressed as 2n + 1
 
 let p = an odd integer, m = an odd integer, k = (p + m + 1)
 
 (2p + 1) + (2m + 1) = 2k
 2p + 2m + 2 = 2k
 2(p + m + 1) = 2k
 2(k) = 2k
 
 2k = 2n = even number by definition
 -Direct Proof
_______________________________________________________________
 The sum of an even integer and it's square is even
 
 2k + (2k)^2 = 2n
 2k + 4k^2 = 2n
 2(k + 2k^2) = 2n
 2(n) = 2n
 
 2n = even number by definition
 -Direct Proof
 ____________________________________________
 If n squared is odd, then n is odd
 
 let 2m + 1 = an odd number, 2k + 1 = an odd number
 n = 2m + 1
 (2m + 1)^2 = 2k + 1
 4m^2 + 4m + 1 = 2k + 1
 2(2m^2 + 2m) + 1 = 2k + 1
 let k = (2m^2 + 2m)
 2(k) + 1 = 2k + 1
 
 2k + 1 is an odd number by definition
 -Direct Proof
 ________________________________________
 
 Part 2: (10 points)
 
 Prove by induction that 1 + 5 + 9 + ... + (4n-3) = n(2n-1)
 
 base case:
 n = 1; (4(1) - 3) = 1(2(1) - 1)
 (4 - 3) = (2 - 1)
 1 = 1  so,
 assume true for k.
 k(2k - 1) + [4(k + 1) - 3] = (k + 1)[2(k + 1) - 1]
 2k^2 - k + 4k + 1 = (k + 1)(2k + 1)
 2k^2 + 3k + 1 = 2k^2 + 3k + 1
 
 k -> k + 1
 _____________________________________________
 Prove that for any positive integer number n, n^3 + 2n is divisible by 3
 
 n^3 + 2n = 3m
 assume true for k
 (k + 1)^3 + 2(k + 1) = 3m
 k^3 + (3k)^2 + 3k + 1 + 2k + 1 = 3m
 (k^3 + 2k) + [(3k)^2 + 3k + 3] = 3m
 (k^3 + 2k) has already been proven to be true
 [(3k)^2 + 3k + 3] = 3m
 3(k^2 + k + 1) = 3m
 let m = (k^2 + k + 1)
 3m = 3m
 
 k -> k + 1
 _______________________________________________________
 Prove that for n >= 1, 9^n − 1 is divisible by 8 for all non-negative integers.
 Hint: 4^(3+1) = 4 * 4^3 Hint: If 9^n - 1 = 8m, then 9^n = 8m + 1
 
 9^(n+1)-1=8m
 (9^n)9-1=8m
 (8m+1)9-1
 72m+8
 8(9m+1)
 let m = 9m+1
 8m = 8m
 
 ______________________________________________________________
