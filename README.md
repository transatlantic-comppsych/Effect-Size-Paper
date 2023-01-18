# When is a small effect actually large and impactful?

[Access the preprint here](https://psyarxiv.com/v3fjk)

## Authors

[Emma G. Carey](https://orcid.org/0000-0002-2294-7989), [Isobel Ridler](https://orcid.org/0000-0003-2196-4733), [Tamsin F. Ford](https://orcid.org/0000-0001-5295-4904), [Argyris Stringaris](https://orcid.org/0000-0002-6264-8377)

## Overview

This repository contains the code and simulated data used in [When is a small effect actually large and impactful?](https://psyarxiv.com/v3fjk). 

Reporting of effect sizes is standard practice in psychology and psychiatry research. However, interpretation of these effect sizes can be meaningless or misleading – in particular, the evaluation of specific effect sizes as “small”, “medium” and “large” can be inaccurate depending on the research context. A real-world example of this is research into the mental health of children and young people during the Covid-19 pandemic. Evidence suggests that clinicians and services are struggling with increased demand, yet population studies looking at the difference in mental health before and during the pandemic report effect sizes that are deemed “small”. In this short review we utilise simulations to demonstrate that a relatively small shift in mean scores on mental health measures can indicate a large shift in the number of cases of anxiety and depression when scaled up to an entire population. This shows that “small” effect sizes can in some contexts be large and impactful.

All analyses were conducted in R. Please reach out to the corresponding author ([Emma G. Carey](ec475@medschl.cam.ac.uk)) with any questions. 

## Steps to reproduce results

Run [`CodeForSmallEffect_v1.Rmd`](../master/CodeForSmallEffect_v1). Please edit the number of repeitions to be less than the current published (1000) if you would just like to run a quick demo.
