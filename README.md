# Minitaur
Pybullet Minitaur with Distributional Policy Gradients

I implemented distributional policy gradient in PyBullet's Minitaur environment.  I added priority replay buffer to the base implementation by Maxim Lapan,<sup>1</sup> which uses architecture described in *A Distributional Perspective on Reinforcement Learning*.<sup>2</sup>  Priority replay buffer is inspired by *Rainbow: Combining Improvements in Deep Reinforcement Learning*.<sup>3</sup>  I applied priority replay buffer to the critic.

<sup>1</sup> [https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On](https://github.com/PacktPublishing/Deep-Reinforcement-Learning-Hands-On)

<sup>2</sup> [https://arxiv.org/pdf/1707.06887.pdf](https://arxiv.org/pdf/1707.06887.pdf)

<sup>3</sup> [https://arxiv.org/pdf/1710.02298.pdf](https://arxiv.org/pdf/1710.02298.pdf)
