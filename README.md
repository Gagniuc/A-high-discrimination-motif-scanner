# A high discrimination motif scanner (two PFMs)

This is a scanner designed to recognise DNA motifs within a long stretch of DNA. It uses two models for discrimination, one model representing the target and the second model representing the background. The model representing the target uses a set of DNA motifs, whereas the model that represents the background uses motifs colected from within the long stretch of DNA being analyzed. The scanner uses the motifs of the two models to compute two position weight matrices (PWMs). It uses the PWMs to search for regions that resemble the motifs from the set that are above the background. But how it does that? Consecutive score values extracted from sliding windows determine the formation of a representative signal above a long stretch of DNA. The score peaks from the signal determine the location of possible motif variations that resemble those in the motif set.

Live demo: https://gagniuc.github.io/A-high-discrimination-motif-scanner/

<kbd><img src="https://github.com/Gagniuc/A-high-discrimination-motif-scanner-two-PFMs-/blob/main/%5BG%5D%20A%20high%20discrimination%20motif%20scanner%20(two%20PFMs).png" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
