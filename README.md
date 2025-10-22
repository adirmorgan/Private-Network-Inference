# Private-Network-Inference

Network Inference is moving towards a SaaS model, and privecy of uploaded data is a major concern.
The area of Private Inference is addressing this problem,
with new results suggesting applications of models using invertable cryptographic techniques, such as Yao's Garbled Circuits.

Using such network adaptation, the bottleneck of computation is located in the *Non-Linear Operations*. 

Hence, researchers focus on trying to reduce non-linear operations, usually ReLU operators.

The paper "Selective Network Linearization for Efficient Private Inference" addressed it in a clean approach, integrated in the training phase, using the LASSO regularization approach for parameters selection.

In this repo I first reconstructed their work, and then moved on to researching other ways to apply the lasso regularization approach, selecting relus to "group togather".
