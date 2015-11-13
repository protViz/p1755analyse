---
title: "Analysing MaxQuant Output with R"
author: "FGC Zurich"
date: "30 September 2015"
output: pdf_document
toc: yes
---

# Prepare mrm table

- nr of assigned spectra (MS2) / versus total spectra
- How many H/L target peptides are identified
- Ratio among H/L of the target peptides
- Intensity of heavy or light over the runs














# Analysed Dataset is IMP_DIV


![](Peptide_Vienna_files/figure-latex/test-1.pdf) 

<!-- # Peptide Evidence -->



# Looking at measurement error

![](Peptide_Vienna_files/figure-latex/unnamed-chunk-3-1.pdf) 




# Looking at MSQC 1 peptide counts










![](Peptide_Vienna_files/figure-latex/unnamed-chunk-8-1.pdf) 

# Look at Intensities (by species)





![](Peptide_Vienna_files/figure-latex/unnamed-chunk-11-1.pdf) 


# Looking at intensities msqc1




![](Peptide_Vienna_files/figure-latex/unnamed-chunk-13-1.pdf) 


![](Peptide_Vienna_files/figure-latex/unnamed-chunk-14-1.pdf) 

# Looking at retention time

![](Peptide_Vienna_files/figure-latex/unnamed-chunk-15-1.pdf) ![](Peptide_Vienna_files/figure-latex/unnamed-chunk-15-2.pdf) 


# Log fold change



```
## Warning in inner_join_impl(x, y, by$x, by$y): joining factors with different levels, coercing to character vector
```

![](Peptide_Vienna_files/figure-latex/unnamed-chunk-16-1.pdf) 

![](Peptide_Vienna_files/figure-latex/unnamed-chunk-17-1.pdf) 


![](Peptide_Vienna_files/figure-latex/unnamed-chunk-18-1.pdf) 




























