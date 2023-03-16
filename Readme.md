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

This table shows the theoretical series of the Propp narremes (german notation) along with the normalized values of the magic squares of sun.
As easily observable, by rotating or transposing a normal magic square, its properties do not change. Since our framework intends to model stories, every position can have only one value. For this purpose I have created a normalized matrix, where for every position (i,j) the value equals to |𝑛/2 −𝑀(𝑖, 𝑗)|, where n is the matrix dimension (in our case, 6x6 = 36). 

![pop](https://github.com/Glottocrisio/GrimmHurst/blob/main/proppfunadjustedvalues.png)
