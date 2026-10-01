---
title: "Field optimization for scalable and distortion-aware process planning in hybrid additive-subtractive manufacturing"
collection: publications
category: manuscripts
permalink: /publication/2026-12-01-Field-optimization-for-scalable-and-distortion-aware-process-planning
date: 2026-12-01
venue: 'ACM Transactions on Graphics (SIGGRAPH Asia 2026)'
citation: 'Yongxue Chen, Tao Liu, Aoran Lyu, Yu Jiang, Neelotpal Dutta, and Charlie C.L. Wang, &quot;Field optimization for scalable and distortion-aware process planning in hybrid additive-subtractive manufacturing.&quot; ACM Transactions on Graphics (SIGGRAPH Asia 2026), vol. 45, no. 6, article no. 252, 16 pages, December 2026.'
author_role: "other"
authors: "Yongxue Chen, Tao LIU, Aoran Lyu, Yu Jiang, Neelotpal Dutta, Charlie C.L. Wang"
selected: false
paperurl: https://doi.org/10.1145/3842560
projecturl: https://yongxue-chen.github.io/hybManuFieldOpt/
videourl: https://youtu.be/HE7gqaH4Iv0
---
This paper presents a field-based optimization method for process planning in hybrid manufacturing, where the goal is to determine a feasible and efficient sequence of additive and subtractive operations for fabricating a target shape. Existing approaches rely on deterministic or discretized formulations, which lead to unoptimized fabrication time and make planning sensitive to voxel resolution. They also do not explicitly account for distortion in intermediate structures formed during manufacturing. To address these limitations, we represent manufacturing states using continuous fields, which scale naturally to models with large dimensions and fine geometric features while enabling smoother fabrication sequences. Based on this representation, we formulate process planning as a numerical optimization problem under multiple objectives, including final shape conformance, intermediate structural strength, manufacturing time, self-supporting and collision-free. Experimental results show that our method can generate distortion-aware process plans on a variety of models while substantially reducing fabrication time through up to a 72.6% reduction in the volume of extra support.
