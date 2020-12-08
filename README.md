# Reinforcement_learning_in_QW
 We implement the off-policy Qlearning algorithm with the goal of maximizing the hybrid entanglement between the walker and the coin degree of freedom in an one-dimensional quantum walk. 
 
# Results

We use the Schmidt norm as a measure of entanglement which is the reward at the final time step of the quantum walk evolution. The Schmidt norm S reached after an evolution of 5-step (blue), 7-step (orange), and 15-step (green) quantum walk with the optimal sequence (solid line) obtained by the Qlearning algorithm and the universal entangling sequence (dotted dashed line) is shown below

![Alt results](https://cfn-live-content-bucket-iop-org.s3.amazonaws.com/journals/1751-8121/53/44/445306/3/aabb54df4_online.jpg?AWSAccessKeyId=AKIAYDKQL6LTV7YY2HIK&Expires=1608068826&Signature=zQrOpKzh%2BnYKYYg9jHCN10Gwy%2FU%3D)

# Training

![Alt results](https://cfn-live-content-bucket-iop-org.s3.amazonaws.com/journals/1751-8121/53/44/445306/3/aabb54df6_online.jpg?AWSAccessKeyId=AKIAYDKQL6LTV7YY2HIK&Expires=1608068826&Signature=cfwpmVZNYQy8gbrcL6ePGTtpAfg%3D)

Learning curves for the optimization problems discussed in the main text. The episodic reward (Schmidt norm) is averaged over 300 [(a) and (b)] or 400 [(c) and (d)]
independent runs. The light blue area corresponds to the confidence interval and dashed lines denote the maximally achievable reward of sqrt(2). (a)–(c) Learning curves for the 5, 7, and 15 step (n) quantum walk where the initial state parameter φ is set to zero and the parameter θ is sampled from a uniform distribution at the beginning of each new episode. (d) Learning curve for the 5 step quantum walk where both initial state parameters φ and θ are sampled at the beginning of each training episode.

# Publication

Find the published version of our work [here](https://iopscience.iop.org/article/10.1088/1751-8121/abb54d)
