# A Triple-Inertial Accelerated Alternating Optimization Method for Deep Learning Training

# Abstract
The stochastic gradient descent (SGD) algorithm has achieved remarkable success in training deep learning models. However, it has several limitations, including susceptibility to vanishing gradients, sensitivity to input data, and a lack of robust theoretical guarantees. In recent years, alternating minimization (AM) methods have emerged as a promising alternative for model training by employing gradient-free approaches to iteratively update model parameters. Despite their potential, these methods often exhibit slow convergence rates. To address this challenge, we propose a novel Triple-Inertial Accelerated Alternating Minimization (TIAM) framework for neural network training. The TIAM approach incorporates a triple-inertial acceleration strategy with a specialized approximation method, facilitating targeted acceleration of different terms in each sub-problem optimization. This integration improves the efficiency of convergence, achieving better performance with fewer iterations. Additionally, we provide a convergence analysis of the TIAM algorithm, including its global convergence properties and convergence rate. Extensive experiments validate the effectiveness of the TIAM method, demonstrating improvements in generalization capability and computational efficiency compared to existing approaches, particularly when applied to the rectified linear unit (ReLU) and its variants.



# Acknowledge
We would like to express our gratitude for the following open-source project:
https://github.com/xianggebenben/mDLAM
