# Author Rebuttal

Dear Reviewers,

Since multiple reviewers have mentioned this issue, **we would like to post an additional rebuttal regarding image consistency.** 

As shown in the results attached at the anonymous URL below, we demonstrate that **consistency can be improved by utilizing the Runway Gen-3 Alpha Turbo model as a 3D-prior model** instead of Zero123++.

**URL:** https://github.com/2024nvs/2024nvs

Please kindly note that the core idea of this work is **not the improvement of consistency itself** but rather **the ability to achieve camera control by combining 3D priors with a 3D-free architecture**, which is the novel insight this work has introduced.

We hope that minor artifacts due to our initial choices in implementation using Zero123++ should be alleviated, after we demonstrate the new results on using Runway Gen-3 Alpha Turbo as 3D prior.

We kindly request Reviewer BRTu, 9Fq5, and yRXV to reconsider their ratings, given our new implementation and results using Runway Gen-3 Alpha Turbo.

## Rebuttal Results

### Synthetic Image
![Synthetic Image](gen3a_syn.jpeg)

### Real Image
![Real Image](gen3a_real.jpeg)
