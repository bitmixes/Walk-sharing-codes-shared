# Walk-sharing-model

## Background

Walking is the most common mode of travel, given its higher levels of accessibility, especially for short trips.
Researchers have suggested that walking has significant health benefits as well as community benefits, and more walkable urban spaces leads to sustainable and liveable communities.
However, challenging walking environments discourage people from walking.
Pedestrians, while walking alone, feel unsafe and vulnerable in certain outdoor spaces at certain times of the day.
Fear of crime has been cited as the most important barrier for which walking becomes unattractive at critical times of the day, even though walking might be convenient otherwise.
Pedestrian route and travel mode choice is often influenced by fear of crime and it forces- pedestrians to avail costlier alternatives, such as taking viable detours or abandoning walking altogether and switching to alternative forms of transport.
Fear of crime reduces the overall walkability of an urban area, reduces the time spent on walking, and thereby disrupts the benefits that are offered by walking.

Traditional approaches aimed at reducing the fear of crime amongst pedestrians are usually not cost-effective, never holistic and take significant time before coming into effect.
Existing research suggests that the absence of people is the major reason for pedestrians feeling fearful while walking through urban spaces at critical times of the day, even when infrastructural elements are conducive for walking.
Pedestrians feel safer when they walk with a companion as compared to walking alone in environments which they perceive as unsafe.
The presence of just another pedestrian nearby boosts natural vigilance, increases sense of security, reduces perceived risk and fear of crime.
People would walk more if they had a walking companion, such as a friend, a colleague, or a family member under critical circumstances.
But, a pedestrian is not guaranteed a walking companion under all critical circumstances.
To overcome this challenge, we have introduced walk-sharing, a hypothetical buddy-service, which is aimed at encouraging people to choose walking when it is viable, and not pursue alternative modes.
In walk-sharing, a potential pedestrian will get matched to another (assumed to be unknown to each other) so that they are able to walk together, instead of walking alone, and thus overcome any potential fear that arises out of seemingly unsafe walking environments.
We used an agent-based modelling platform GAMA (tailored for building spatially explicit agent-based simulations) to model walk-sharing, established proof of concept using synthetic data, and tested its technical viability under under real-world data-driven scenarios to understand the conditions in which walk-sharing will produce acceptable outcomes.

## What is walk-sharing?

In walk-sharing, a potential pedestrian will get matched to another so that they are able to walk together, instead of walking alone, and thus overcome any potential fear that arises out of seemingly unsafe walking environments. 
Walk-sharing makes an attempt to ensure such spatio-temporal overlap between at least two pedestrians so that they can walk together while trying to optimise related costs (waiting time, detour distance) for both.
This novel intervention is aimed at reviving the appeal of walking as a travel mode even at critical times of the day and the benefits that should follow thereafter.

## Following up from previous research

Walk-sharing is a cost-effective and proactive approach that promises to improve pedestrian safety and has been shown to be technically (theoretically) viable. 
Yet, the practical viability of walk-sharing is largely dependent on community acceptance, which has not, until now, been explored. 
Gaining useful insights on the community’s spatio-temporal and social preferences in regard to walk-sharing will ensure the establishment of practical viability of walk-sharing in a real-world urban scenario. 
We aim to derive practical viability using defined performance metrics (waiting time, detour distance, walk-alone distance and matching rate) and by investigating the effectiveness of walk-sharing in terms of its major objective of improving pedestrian safety and safety perception. 
We make use of the results from a web-based survey on the public perception on our proposed walk-sharing scheme. 
Findings are fed into an existing agent-based walk-sharing model to investigate the performance of walk-sharing and deduce its practical viability in urban scenarios.

## GAMA

For developing our agent-based simulation model, we chose GAMA as our platform. 
> [GAMA](https://gama-platform.github.io/) (GIS Agent-based Modeling Architecture) 
is a modeling and simulation development environment for building spatially explicit agent-based simulations.
GAML is the language used in GAMA, coded in Java. 

## Publication

If you use this model or parts of it, make sure you cite our publication [Investigating the practical viability of walk-sharing in improving pedestrian safety](https://doi.org/10.1007/s43762-021-00020-z).


