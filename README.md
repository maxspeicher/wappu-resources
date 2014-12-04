WaPPU: Was that Page Pleasant to Use?
=====================================

## Abstract

Usability is a crucial quality aspect of web applications, as it guarantees customer satisfaction and loyalty. Yet, effective approaches to usability evaluation are only applied at very slow iteration cycles in today's industry. In contrast, conversion-based split testing seems more attractive to e-commerce companies due to its more efficient and easy-todeploy nature. We introduce Usability-based Split Testing as an alternative to the above approaches for ensuring web interface quality, along with a corresponding tool called WaPPU. By design, our novel method yields better effectiveness than using conversions at higher efficiency than traditional evaluation methods. To achieve this, we build upon the concept of split testing but leverage user interactions for deriving quantitative metrics of usability. From these interactions, we can also learn models for predicting usability in the absence of explicit user feedback. We have applied our approach in a split test of a real-world search engine interface. Results show that we are able to effectively detect even subtle differences in usability. Moreover, WaPPU can learn usability models of reasonable prediction quality, from which we also derived interaction-based heuristics that can be instantly applied to search engine results pages.

## Publications

- Maximilian Speicher, Andreas Both, and Martin Gaedke (2014). "Ensuring Web Interface Quality through Usability-based Split Testing". In: *Proc. ICWE*. http://link.springer.com/chapter/10.1007/978-3-319-08245-5_6
- Maximilian Speicher, Andreas Both, and Martin Gaedke (2014). "WaPPU: Usability-based A/B Testing". In: *Proc. ICWE (Demos)*. http://link.springer.com/chapter/10.1007/978-3-319-08245-5_47
- Maximilian Speicher, Andreas Both, and Martin Gaedke (2013). "Was that Webpage Pleasant to Use? Predicting Usability Quantitatively from Interactions". In: *Proc. ICWE Workshops*. http://link.springer.com/chapter/10.1007/978-3-319-04244-2_33

## Resources

This repository contains:

- The complete list of interaction features and complete user study results (onlineAppendix.pdf).
- The correlations of the original search engine results page for the most representative user context *HD screen / new user* (correlations_A_HD_notFamiliar.csv).
- Training data, usability model and test set for each of the investigated usability factors (context *HD screen / new user*). To be used with [WEKA](http://www.cs.waikato.ac.nz/ml/weka/).
