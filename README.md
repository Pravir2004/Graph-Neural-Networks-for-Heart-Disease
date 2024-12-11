# Graph-Neural-Networks-for-Heart-Disease

Abstract
Growth of advancements in machine learning have
enabled better analyses of healthcare data. Having the ability
to predict heart disease, a major cause of death, is fundamen-
tally important for the timely diagnosis and treatment of an
individual. In this research, we present a framework that uses
graph neural networks (GNNs) to model relationships among
patient characteristics and predict heart disease outcomes. We
implement the SAGEConv architecture for graph convolutions,
along with feature normalization and dropout techniques to
enhance learning robustness.
With training-validation-test splitting and neighbor sampling,
we made sure the test was performed on a balanced-testing.
To interpret the results, visualization techniques, including heat
maps, graph splits, and confusion matrices, were performed. The
model gave a test accuracy of 84.47% and inspired confidence
in identifying patterns from the patient data.
Our findings illustrate the immense promise of GNNs for
the predictive aspects of healthcare, showing their capacity to
eﬀectively model complex relationships. The framework proves
important as a starting point for integrating graph-based learning
into significantly high-stakes medical decision-making, with room
for further improvements.
Index Terms—Heart Disease Prediction, Graph Neural Net-
works (GNNs), SAGEConv Architecture, Healthcare Analytics,
Machine Learning in Medicine


This study indicates the capacity of GNNs to prognosticate
on heart disease, achieving a test accuracy of 84.47% with
balanced performances with respect to recall, precision and
F1-score metrics. This work emphasizes the great value of
harnessing graph-based learning for understanding the re-
lationships between patients, which are often neglected in
classical models. Meaningful features for predictive power
include thalach, oldpeak, and cholesterol, which follow es-
tablished medical perspectives and underscore the model’s
interpretability.
The implications for healthcare are enormous and extend
beyond prediction accuracy to allow greater insight into patient
data through graph visualizations and feature importance heat
maps. This work aims to treat patients as connected nodes
where each patient imposes a glycine to promote personalized
treatments of disease, achieve personal diagnosis at an earlier
stage, and make better use of clinical resources. In the future
work, the main shortcoming of this work will be to address the
high computational complexity of the full graph and the less
available clinical samples. The introduction of sparse graphs,
the use of domain-specific thresholds, and resource allocation
to bigger datasets will expand scalability and applicability to
real-world situations. Temporal graphs could also be integrated
into the model to account for such time-dependent changes in
health.
Generally, the work strengthens the prospect of GNN in-
corporation into health analytics and further opens panoramic
perspectives of accurate and interpretable medical prediction.
