---
layout: single
title:  "II. Proteogenomic database creation"
date:   2022-03-17 19:03 -0800
categories: jekyll update
header:
  # image: /assets/images/Spritz-01.png
  teaser: /assets/images/Spritz-01.png
author_profile: true
---

Each of us has thousands of variations in our genomes, alternative splicing in our transcriptomes, and post-translational modifications (PTMs) adorning our proteins that make us unique. These variations are not captured in canonical protein databases used for proteomic searches, and so they are invisible to traditional database-centric means of identifying proteins. I combined and refined methods to construct databases with these variations and modifications, and I was able to identify thousands of peptides that were unique to each of 10 human cell lines, illustrating the power of sample-specific databases to reveal variation unique to individuals, cancers, and non-human primates in another study using the software I developed.

These approaches have typically appended variant peptides to the end of the proteomic database before proteomic searches, and I also developed methods to identify and encode full-length variant-containing proteoforms within the tool Spritz. This tool has been successfully applied to identify variant-containing proteoforms in Jurkat cells, as well as in sorted human blood cells in an article published in the journal _Science_.

![spritz](/assets/images/Spritz-01.png)

## Research papers
(1) Melani, R. D.; Gerbasi, V. R.; Anderson, L. C.; Sikora, J. W.; Toby, T. K.; Hutton, J. E.; Butcher, D. S.; Negrão, F.; Seckler, H. S.; Srzentić, K.; Fornelli, L; Camarillo, J. M.; LeDuc, R. D.; **Cesnik, A. J.**; Lundberg, E., Greer, J. B.; Fellers, R. T.; Robey, M. T.; DeHart, C. J.; Forte, E.; Hendrickson, C. L.; Abbatiello, S. E.; Thomas, P. M.; Kokaji, A. I.; Levitsky, J.; Kelleher, N. L. “The Blood Proteoform Atlas: A compositional map of proteoforms in human haematopoietic cells.” Science 2022, 375, 6579, 411–418.

(2) **Cesnik, A. J.**; Miller, R. M.; Ibrahim, K.; Lu, L.; Shortreed, M. R.; Frey, B. L.; Smith, L. M. “Spritz: A Proteogenomic Database Engine.” Journal of Proteome Research 2021, 20, 4, 1826–1834.

(3) **Cesnik, A. J.**; Shortreed, M. R.; Sheynkman, G. M.; Frey, B. L.; Smith, L. M. “Human Proteomic Variation Revealed by Combining RNA-Seq Proteogenomics and Global Post-Translational Modification (G-PTM) Search Strategy.” Journal of Proteome Research 2016, 15, 800–808. **\*\*American Chemical Society Editor’s Choice**

(4) Proffitt, J. M.; Glenn, J.; **Cesnik, A. J.**; Jadhav, A.; Shortreed, M. R.; Smith, L. M.; Kavanagh, K.; Cox, L. A.; Olivier, M. “Proteomics in non­human primates: Utilizing RNA-­seq data to improve protein identification by mass spectrometry in vervet monkeys.” BMC Genomics 2017, 18, 887.

(5) Sheynkman, G. M.; Shortreed, M. R.; **Cesnik, A. J.**; Smith, L. M. “Proteogenomics: Integrating Next­-Generation Sequencing and Mass Spectrometry to Characterize Human Proteomic Variation.” Annual Review of Analytical Chemistry 2016, 9, 512–545.