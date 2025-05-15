**Upkie** is an open source wheeled biped robot design with wheels for balancing and legs to negotiate uneven terrains. Upkies are designed to be buildable using tools and components ordered online, like mjbots actuators.

- [Getting started](https://github.com/upkie/upkie?tab=readme-ov-file#getting-started)
- Hardware: [Building an Upkie](https://github.com/upkie/upkie/wiki)
- Software: [Documentation](https://upkie.github.io/upkie/)

Behaviors are distributed in *agent* repositories. For instance, you can compare how balancing is implemented by different approaches:

- Model predictive control: [MPC balancer](https://github.com/upkie/mpc_balancer)
- Reinforcement learning: [PPO balancer](https://github.com/upkie/ppo_balancer)
- Classical control: [PID balancer](https://github.com/upkie/pid_balancer)

Head over to the [new\_agent](https://github.com/upkie/new_agent) template to start implementing your own behaviors 👷
