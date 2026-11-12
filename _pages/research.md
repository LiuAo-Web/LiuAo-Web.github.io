---
layout: single
title: "研究/Research"
permalink: /research/
author_profile: true
---

我的研究聚焦土地利用、交通与环境的一体化建模与优化，综合运用交通建模、机器学习、优化算法、地理空间分析和环境影响评估等方法，评估新兴交通技术及相关规划与政策对可达性和环境的影响，并探索交通系统与城市空间的协同优化策略。

My research focuses on integrated modeling and optimization of land use, transportation, and the environment. Drawing on transportation modeling, machine learning, optimization algorithms, geospatial analysis, and environmental impact assessment, I evaluate how emerging transportation technologies and related planning and policy measures affect accessibility and the environment, and explore strategies for the coordinated optimization of transportation systems and urban space.

研究主题/Research Themes
======

共享自动驾驶汽车与城市可持续发展
------
共享自动驾驶汽车时代即将到来，一系列与可达性与可持续性相关的问题随之而来。SAVs是否会提高可达性、改善环境？还是只是提高机动性并促使城市进一步蔓延？这取决于当前的规划方法和应对SAVs技术的政策手段。为此，本方向期望通过土地利用和交通整合视角，定量评估SAVs技术的长期可达性与环境效应，并制定相应的SAVs定价政策，最大限度地发挥SAVs的效益，减少SAVs对可达性与环境的潜在负面影响。

### Shared Autonomous Vehicles and Urban Sustainability

The era of shared autonomous vehicles (SAVs) is approaching, and with it come a series of questions about accessibility and sustainability. Will SAVs improve accessibility and the environment, or will they merely increase mobility and drive further urban sprawl? The answer depends on current planning approaches and on the policy instruments adopted in response to SAV technology. From an integrated land use and transportation perspective, this research line quantitatively evaluates the long-term accessibility and environmental effects of SAVs and designs corresponding SAV pricing policies, so as to maximize the benefits of SAVs and reduce their potential negative impacts on accessibility and the environment.

<figure class="research-figure">
  <img src="{{ '/images/research/sav-sustainability.webp' | relative_url }}" alt="共享自动驾驶汽车定价与土地利用、交通和环境效应评估框架" width="2000" height="1246" loading="lazy" decoding="async">
</figure>

{% include research-outputs.html publications="/publication/energy-environment-savs|/publication/shared-autonomous-vehicles-review" %}

<hr class="research-divider">

逻辑驱动的多源交通大数据分析
------
多源交通数据为识别出行规律、诊断系统问题与评估政策效应提供了丰富信息，但不同数据在时空尺度、覆盖范围和观测对象上的差异，以及数据关联与行为机制之间的脱节，可能影响分析结果的可靠性。本方向以交通运行规律和出行行为逻辑为基础，整合交通、土地利用、人口与环境等数据，研究多源信息融合、时空异质性及关键因素之间的交互关系，结合统计分析与可解释机器学习，服务于交通需求识别、公交问题诊断和环境效应评估。

### Logic-Driven Analysis of Multi-Source Transportation Big Data

Multi-source transportation data provide rich information for identifying travel patterns, diagnosing system problems, and evaluating policy effects. However, differences among data sources in spatiotemporal scale, coverage, and observed subjects, together with the disconnect between data correlations and behavioral mechanisms, may undermine the reliability of analytical results. Grounded in the regularities of traffic operations and the logic of travel behavior, this research line integrates transportation, land use, population, and environmental data to study multi-source information fusion, spatiotemporal heterogeneity, and the interactions among key factors. Combining statistical analysis with interpretable machine learning, it supports travel demand identification, bus system diagnosis, and environmental impact assessment.

<figure class="research-figure">
  <img src="{{ '/images/research/data-method.webp' | relative_url }}" alt="融合多源数据、机器学习与环境评估的空气质量预测技术路线" width="1865" height="2400" loading="lazy" decoding="async">
</figure>

{% include research-outputs.html publications="/publication/urban-air-quality-sustainability|/publication/built-environment-travel-time-variability|/publication/bus-diagnosis-review" %}

<hr class="research-divider">

土地利用和交通整合规划
------
城市不同性质的土地利用在空间中的彼此分离是产生交通需求的根源。而城市交通系统反过来又是影响城市土地利用的一个重要因素。城市交通与土地利用之间存在着极为复杂的相互影响、制约关系，这种关系构成了土地利用、可达性、交通设施以及交通需求间的“螺旋式”互动机制。然而，现有的交通规划模型和方法往往被动的服务于既定的土地利用规划，缺少两者间的反馈机制，使现有的规划成果往往具有一定的局限性。为此，本方向关注城市土地利用和交通间的互动反馈关系，从土地利用和交通整合的角度，丰富和拓展现有的交通规划理论、模型和方法。

### Integrated Land Use and Transportation Planning

The spatial separation of different types of urban land use is the root cause of travel demand, and the urban transportation system in turn is an important factor shaping urban land use. Urban transportation and land use influence and constrain each other in highly complex ways, forming a “spiral” interaction among land use, accessibility, transportation facilities, and travel demand. However, existing transportation planning models and methods often passively serve predetermined land use plans and lack a feedback mechanism between the two, which often limits the resulting plans. This research line therefore focuses on the interactive feedback between urban land use and transportation and, from an integrated land use and transportation perspective, enriches and extends existing transportation planning theories, models, and methods.

<figure class="research-figure">
  <img src="{{ '/images/research/land-use-transport-feedback-cycle.webp' | relative_url }}" alt="土地利用与交通的互动反馈循环" width="2000" height="2000" loading="lazy" decoding="async">
</figure>

{% include research-outputs.html publications="/publication/road-congestion-pricing-review" %}

<hr class="research-divider">

机器学习与交通系统优化
------
交通系统中的定价、设施布局与运营决策通常涉及多目标、非线性和复杂反馈，部分决策效果需要借助计算成本较高的仿真模型评估，给优化求解带来挑战。为此，本方向重点研究复杂输入与系统响应之间的映射关系，利用贝叶斯优化算法、大语言模型等多目标优化方法，提高求解效率与解的质量。围绕共享自动驾驶汽车定价、公交充电设施布局等问题，提出了一系列兼顾可达性、运行成本与环境效益的决策方法。

### Machine Learning and Transportation System Optimization

Pricing, facility location, and operational decisions in transportation systems typically involve multiple objectives, nonlinearity, and complex feedback, and the effects of some decisions must be evaluated with computationally expensive simulation models, which makes optimization challenging. This research line therefore studies the mapping between complex inputs and system responses, and applies multi-objective optimization methods such as Bayesian optimization and large language models to improve solution efficiency and quality. Focusing on problems such as SAV pricing and electric bus charging station location, it has proposed a series of decision-making methods that balance accessibility, operating costs, and environmental benefits.

<figure class="research-figure">
  <img src="{{ '/images/research/bus-charging.webp' | relative_url }}" alt="电动公交充电站选址与土地利用交通一体化优化框架" width="1722" height="2400" loading="lazy" decoding="async">
</figure>

{% include research-outputs.html publications="/publication/electric-bus-charging-locations|/publication/joint-pricing-savs-congestion" %}
