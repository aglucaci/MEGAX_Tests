# MEGAX_Tests

Various performance experiments with methods available in MEGA-X

Data includes an already codon-aware alignment.

Substitution Matrix Estimates (SME) follow a Uniform distribution unless otherwise noted. All other parameters are defaults.

Gamma distributed SME use a pre-computed NJ tree available in the data folder

## Example Analysis Options - Substitution Matrix
```
    Tree to Use                     :  Automatic (Neighbor-joining tree)
    Statistical Method              :  Maximum Likelihood
Substitution Model
    Substitutions Type              :  Nucleotide
    Model/Method                    :  Jukes-Cantor model
Rates and Patterns
    Rates among Sites               :  Gamma Distributed (G)
    No of Discrete Gamma Categories :  5
Data Subset to Use
    Gaps/Missing Data Treatment     :  Use all sites
    Select Codon Positions          :  1st,2nd,3rd,Non-Coding
    Branch Swap Filter              :  None
``` 

## Example Analysis Caption - Substitution Matrix, Gamma distributed
```
NOTE.-- Each entry is the probability of substitution (r) from one base (row) to another base (column). Substitution pattern and rates were estimated under the General Time Reversible model (+G) [1]. A discrete Gamma distribution was used to model evolutionary rate differences among sites (5 categories, [+G], parameter = 0.3468). Rates of different transitional substitutions are shown in bold and those of transversionsal substitutions are shown in italics. Relative values of instantaneous r should be considered when evaluating them. For simplicity, sum of r values is made equal to 100, The nucleotide frequencies are A = 26.48%, T/U = 20.21%, C = 24.43%, and G = 28.88%. For estimating ML values, a user-specified topology was used. The maximum Log likelihood for this computation was -36926.431. This analysis involved 319 nucleotide sequences. Codon positions included were 1st+2nd+3rd+Noncoding. There were a total of 1902 positions in the final dataset. Evolutionary analyses were conducted in MEGA X [2].


1. Nei M. and Kumar S. (2000). Molecular Evolution and Phylogenetics. Oxford University Press, New York.
2. Kumar S., Stecher G., Li M., Knyaz C., and Tamura K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. Molecular Biology and Evolution 35:1547-1549.
Disclaimer: Although utmost care has been taken to ensure the correctness of the caption, the caption text is provided "as is" without any warranty of any kind. Authors advise the user to carefully check the caption prior to its use for any purpose and report any errors or problems to the authors immediately (www.megasoftware.net). In no event shall the authors and their employers be liable for any damages, including but not limited to special, consequential, or other damages. Authors specifically disclaim all other warranties expressed or implied, including but not limited to the determination of suitability of this caption text for a specific purpose, use, or application.
```

## Simple NJ Tree Construction

```
Evolutionary relationships of taxa 
The evolutionary history was inferred using the Neighbor-Joining method [1]. The optimal tree with the sum of branch length = 7.01208453 is shown. The tree is drawn to scale, with branch lengths in the same units as those of the evolutionary distances used to infer the phylogenetic tree. The evolutionary distances were computed using the Maximum Composite Likelihood method [2] and are in the units of the number of base substitutions per site. This analysis involved 319 nucleotide sequences. Codon positions included were 1st+2nd+3rd+Noncoding. All ambiguous positions were removed for each sequence pair (pairwise deletion option). There were a total of 1902 positions in the final dataset. Evolutionary analyses were conducted in MEGA X [3].


1. Saitou N. and Nei M. (1987). The neighbor-joining method: A new method for reconstructing phylogenetic trees. Molecular Biology and Evolution 4:406-425.
2. Tamura K., Nei M., and Kumar S. (2004). Prospects for inferring very large phylogenies by using the neighbor-joining method. Proceedings of the National Academy of Sciences (USA) 101:11030-11035.
3. Kumar S., Stecher G., Li M., Knyaz C., and Tamura K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. Molecular Biology and Evolution 35:1547-1549.
Disclaimer: Although utmost care has been taken to ensure the correctness of the caption, the caption text is provided "as is" without any warranty of any kind. Authors advise the user to carefully check the caption prior to its use for any purpose and report any errors or problems to the authors immediately (www.megasoftware.net). In no event shall the authors and their employers be liable for any damages, including but not limited to special, consequential, or other damages. Authors specifically disclaim all other warranties expressed or implied, including but not limited to the determination of suitability of this caption text for a specific purpose, use, or application.

```
   
## Todo: Use a fixed tree
