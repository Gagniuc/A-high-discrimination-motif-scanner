# A high discrimination motif scanner (two PFMs)

This is a scanner designed to recognise DNA motifs within a long stretch of DNA. The scanner uses a motif set to compute a position weight matrix (PWM). It uses the PWM to search for regions that resemble the motifs from the set. But how it does that? Consecutive score values extracted from sliding windows determine the formation of a representative signal above a long stretch of DNA. The score peaks from the signal determine the location of possible motif variations that resemble those in the motif set.

Live demo: https://gagniuc.github.io/A-high-discrimination-motif-scanner/

<kbd><img src="https://github.com/Gagniuc/A-high-discrimination-motif-scanner-two-PFMs-/blob/main/%5BG%5D%20A%20high%20discrimination%20motif%20scanner%20(two%20PFMs).png" /></kbd>

# References

- <i>Paul A. Gagniuc. Algorithms in Bioinformatics: Theory and Implementation. John Wiley & Sons, Hoboken, NJ, USA, 2021, ISBN: 9781119697961.</i>
