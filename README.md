# ROCKY_OMNI3WHEEL_ART
Implementación de PRM en un robot holonómico de tres ruedas

El presente artículo se centra en el desarrollo de una plataforma experimental denominada ROCKY, un robot holonómico de tres ruedas que implementa el algoritmo PRM (Probabilistic Roadmap), diseñado para su navegación en entornos con obstáculos fijos. Al utilizar este algoritmo en un robot omnidireccional de tres ruedas, se aprovechan sus características de maniobrabilidad y capacidad de movimiento, al tiempo que se reducen tanto la complejidad como los costos de implementación, tanto económicos como computacionales.

El objetivo principal de ROCKY es permitir que el robot se desplace de manera autónoma en entornos con obstáculos. Para lograrlo, se emplea comunicación inalámbrica y se utiliza el módulo Jetson Nano, lo que facilita el trabajo con ROS (Robot Operating System).

El proyecto se organiza en tres etapas:

La conexión de la Jetson Nano con Matlatb vía Wi-Fi https://github.com/itzchav/MATLAB_Y_ROS

El cálculo de la traycetoria con Matlab https://github.com/Bomar01/ROCKY_Omni3Wheel.git

El control cinemático https://github.com/KikeBotEngineer/Omni3MotorControl.git
