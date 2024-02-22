# RL-Traffic (please email me if interested in full paper)

Inefficient traffic light control at major road intersections can lead to significant problems such as
long travel delays, wasteful energy usage, and even vehicular accidents. Unfortunately, existing traffic
light control systems often rely on fixed programs that fail to consider real-time traffic conditions or
only take limited factors into account. As a result, traffic flow at intersections is often suboptimal,
which lead to the problems mentioned above as well as other associated issues. Therefore, more
advanced methods are needed to efficiently manage traffic flow at intersections, which can optimize
traffic patterns and minimize the negative impacts of traffic congestion.
We explore this issue of inefficient traffic light control with reinforcement learning (RL). Because
intersections come in many different forms with varying outside factors such as numbers of cars per
lane, we thought using reinforcement learning to tackle this problem would be a promising approach
because it allows us to consider the dynamic and complex intersection environment while providing
adaptive decision-making based on a given scenario. By training an agent to learn from experience
and interact with the traffic environment, we aim to develop a traffic light control system that can
intelligently adapt to changing traffic conditions and optimize traffic patterns.
Within our setup, the input to our algorithm is a state that represents an intersection which consists of
lanes each with some number of vehicles. We then use our reinforcement learning model to learn
the predicted action (which lane we are turning on/off; we only use red and green lights) and the
associated reward for each state transition, and then output an integer waiting time that represents
how long it took for our experiment to finish simulating. We will provide more explanation on our
methodology in the Methods section.
In a real world scenario, the potential benefits of efficient traffic light control are significant, including
reduced travel times, decreased vehicular casualties, and enhanced overall traffic flow.
