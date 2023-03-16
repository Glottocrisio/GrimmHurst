# Self-similarity in texts
## Fabulous contributions to computational narratology

Most of the pictures uploaded to this repository display graphically the related vector as a .txt file format.
Therein, each self-information value equals to _I_ (in the following the complete list of computed values):

SS: Amount of sentences.  
#S: Amount of propositions in a sentence.  
#W: Amount of words in a proposition.  
DWL: Average word length.  
DSL: Average proposition length.  
ADD: Average Dependency Distance.  
#P: Amount of narremes in a single sentence.  
I: ADD * #P.  
O: I-#W Ratio.  
F: ADD + #P.  
A: F-#W Ratio.  


Among all values retrieved over a small manually-annotated corpus of german fairy-tales, the self-similarity of 
every vector is assessed by computing the Hurst Exponent.
Here for instance the comparison of all Hurst parameters for the vectors related to every linguistic levels for the folk-tale 
"The king of bees":

![pop](https://github.com/Glottocrisio/GrimmHurst/blob/main/bienek%C3%B6niginhurst.png)

The following table shows the theoretical series of the Propp narremes (german notation) along with the normalized values of the magic squares of sun.
As easily observable, by rotating or transposing a normal magic square, its properties do not change. Since our framework intends to model stories, every position can have only one value. For this purpose I have created a normalized matrix, where for every position (i,j) the value equals to |𝑛/2 −𝑀(𝑖, 𝑗)|, where n is the matrix dimension (in our case, 6x6 = 36). Only the sum of the values for each column remains the same.

![pop](https://github.com/Glottocrisio/GrimmHurst/blob/main/proppfunadjustedvalues.png)

The overlapping between values and narremes is nothing but a fruit of coincidence. Even demonstrating some "ontological" relationship between the 36 proppian functions and the 36 values of the magic square 6x6, a cabbalistic more than scientific attempt, we would still be far from the goal of modelling the interestingness in longer and more complex literature products, whereby such a simplistic attempt cannot work. 
Nevertheless, such an utopical demonstration would let to establish some parameters by means of which it would be possible to fine-tune the final (probabilistic and surprisal based) equation, on the basis of the cognitivist assumption that the older a belief is, the stronger it will be rooted in our collective imagination.
