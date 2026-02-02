This project estimates the parameters of a Gaussian probability density function using NO₂ air pollution data.

What this program does

Loads air quality dataset

Takes NO₂ values

Applies roll-number-based transformation:

𝑧=𝑥+𝑎𝑟sin⁡(𝑏𝑟𝑥)
z=x+ar
sin(brx)
Treats the transformed values as samples from a Gaussian distribution

Computes:

μ (mean)

λ (related to variance)

c (normalization constant)

Calculates the density:

𝑝^(𝑧)=𝑐𝑒-𝜆(𝑧−𝜇)2p^(z)=ce
−λ(z−μ)
2

Plots the probability density curve
