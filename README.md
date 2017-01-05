#DNA_sequence
The DNA_sequence is a simple module that contains one object: FastaDNA for handling DNA sequences in FASTA format.

It has two attributes:
name, for he name of the sequence.
sequence, which is the DNA sequence itself.

It has three methods:

translate(frame):
return a string with the translation of the DNA sequence into a protein sequence.
It allow the 3 different reading frame to be operated.

If frame=2, the translation begin at the second base.
If frame=3, the translation begin at the third base.
For every other value of frame, the translation begin at the first base.

reverse():
takes no argument and return a string with the DNA sequence reversed.

reverse_complement():
takes no argument and return a string with the complementary strand of DNA reversed.
