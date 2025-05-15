**Upkie** is an open source wheeled biped robot design with wheels for balancing and legs to negotiate uneven terrains. Upkies are designed to be buildable using tools and components ordered online, like mjbots actuators.

- Getting started: [Videos](https://www.youtube.com/@upkie) and [First-time example](https://github.com/upkie/upkie?tab=readme-ov-file#getting-started)
- Hardware: [Bill of materials](https://github.com/upkie/upkie/wiki/Bill-of-materials), [Build instructions](https://github.com/upkie/upkie/wiki) and [CAD files](https://github.com/upkie/upkie_parts)
- Software: [Installation](https://github.com/upkie/upkie#installation), [Examples](https://github.com/upkie/upkie/tree/main/examples) and [Documentation](https://upkie.github.io/upkie/)

## Agents

Standalone Upkie agents are distributed in their own repositories:

- [MPC balancer](https://github.com/upkie/mpc_balancer): balance in place using model predictive control.
- [Pink balancer](https://github.com/upkie/pink_balancer): a more advanced agent that can crouch and stand up while balancing.
- [PPO balancer](https://github.com/upkie/ppo_balancer): balance in place with a policy trained by reinforcement learning.
- [PID balancer](https://github.com/upkie/pid_balancer): legacy agent used to test new Upkies with minimal dependencies.

Head over to the [new\_agent](https://github.com/upkie/new_agent) template to create your own, and feel free to open a PR here to add your agent to the list.
