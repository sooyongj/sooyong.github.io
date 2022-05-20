---
title: "Improving Classifier Confidence using Lossy Label-Invariant Transformations"
collection: publications
permalink: /publication/2021_improving_classifier
excerpt: 'Providing reliable model uncertainty estimates is imperative to enabling robust decision making by autonomous agents and humans alike. In this paper, we present the recursive lossy label-invariant calibration (ReCal) technique that leverages label-invariant transformations to recursively group (and calibrate) inputs. We show that ReCal outperforms other calibration methods on multiple datasets, especially, on large-scale datasets such as ImageNet.'
date: 2021-03-18
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS) 2021'
paperurl: 'http://proceedings.mlr.press/v130/jang21a/jang21a.pdf'
---

Abstract: Providing reliable model uncertainty estimates is imperative to enabling robust decision making by autonomous agents and humans alike. While recently there have been significant advances in confidence calibration for trained models, examples with poor calibration persist in most calibrated models. Consequently, multiple techniques have been proposed that leverage labelinvariant transformations of the input (i.e., an input manifold) to improve worst-case confidence calibration. However, manifold-based confidence calibration techniques generally do not scale and/or require expensive retraining when applied to models with large input spaces (e.g., ImageNet). In this paper, we present the recursive lossy label-invariant calibration (ReCal) technique that leverages label-invariant transformations of the input that induce a loss of discriminatory information to recursively group (and calibrate) inputs – without requiring model retraining. We show that ReCal outperforms other calibration methods on multiple datasets, especially, on large-scale datasets such as ImageNet.
