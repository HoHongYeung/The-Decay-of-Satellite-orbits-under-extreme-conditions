# The-Decay-of-Satellite-orbits-under-extreme-conditions
Satellites are an important foundation for tasks such as communication, navigation and weather forecasting. In
this project, we analyze the impact of extreme conditions on satellite drag, a critical factor contributing to orbital decay. Using a new dataset from the Swarm A satellite provided by ESA, we build a GLM-based satellite orbit prediction model. The iterative satellite orbital altitude is influenced by spatial density (Density), Earth's geomagnetic field interference (Kp
index), geomagnetic storm strength (DST index), Earth's magnetic field activity (ap index), and satellite position (latitude
and longitude).The GLM prediction model achieved an RMSE of 0.2723, indicating its effectiveness. We also explore
alternative modeling approaches, including BP neural networks, decision trees, and gradient descent methods, providing
valuable insights for engineers when selecting models. Analyzing the dataset reveals that Density has the most significant
impact on altitude. Specifically, when Density is around 9.233E-12, satellite orbit decay becomes prominent. High Kp values
(>70) and significant altitude changes (>80) correlate with rapid satellite orbit decay. This study contributes to our
understanding of satellite behavior in extreme conditions, aiding in satellite mission planning and maintenance.
