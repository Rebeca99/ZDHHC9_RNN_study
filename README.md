The current Jupyter Notebook shows the RNN modelling pipeline.

DATA used for RNN training (as labels):
- The empirical data used as RNN labels is private (sensitive data) and it reflects group-level MEG-derived AEF responses for the Control and ZDHHC9 groups. Prior to RNN modelling, the MEG data was preprocessed with MNE Python (version 1.0.3)
- in Python 3.10. Cluster-based permutation testing was employed to determine the magnetometers (sensors) where significant differences between standard-induced and deviant-induced responses existed. Then, the responses from the overlapping
- sensors between the 2 groups (Controls and ZDHHC9) where significant standard-deviant differences existed in each group, were then reduced to that of the channel, in each group, that has the largest AEF amplitude. Next, AEF responses
- were averaged across participants for that channel to obtain one group-level measure for each group.


RNN modelling:
- The current Jupyter Notebook includes RNN model training with control data as well RNN weight perturbation experiments (1-3) and subsequent model testing.
- The figures found in the manuscript can be generated with the existing code.
