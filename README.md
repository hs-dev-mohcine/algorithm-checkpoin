# algorithm-checkpoint
Algorithm: Count Sentence Information
Variables:

length, words, vowels : integer
ch : character
Begin

length ← 0
words ← 1
vowels ← 0
Read ch
While ch ≠ '.' do

5.1 length ← length + 1

5.2 If ch in {a, e, i, o, u, A, E, I, O, U} then

    vowels ← vowels + 1

5.3 If ch = ' ' then

    words ← words + 1

5.4 Read ch
EndWhile
length ← length + 1  // include the period
Write "Length = ", length
Write "Words = ", words
Write "Vowels = ", vowels
End
