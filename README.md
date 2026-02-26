# ros2_demo_repository

<p align="center">
  <img src="https://img.shields.io/github/v/release/OpenAutomatedDriving/ros2_demo_repository"/>
  <img src="https://img.shields.io/github/license/OpenAutomatedDriving/ros2_demo_repository"/>
  <a href="https://github.com/OpenAutomatedDriving/ros2_demo_repository/actions/workflows/docker-ros.yml"><img src="https://github.com/OpenAutomatedDriving/ros2_demo_repository/actions/workflows/docker-ros.yml/badge.svg"/></a>
  <a href="https://OpenAutomatedDriving.github.io/ros2_demo_repository"><img src="https://github.com/OpenAutomatedDriving/ros2_demo_repository/actions/workflows/docs.yml/badge.svg"/></a>
  <img src="https://img.shields.io/badge/ROS 2-jazzy-22314e"/>
</p>

- [Auto-generated Package Documentation](#auto-generated-package-documentation)

TODO
- note that this is a component of the stack, link to main repo
- short description and purpose of the package
- screenshot/catchy media showing package's output or similar (if applicable)
- container image built by docker-ros
- example launch command including launch args
- implementation details: arbitrarily long description of how the package/node works internally; useful for someone working on the source code
- hardware requirements (amd/arm, CPU, GPU, RAM, ...) (CGE)
- safety requirements/guarantees: "ODD"-boundaries, fallback behavior, ..  (CGE)

## Auto-generated Package Documentation

### `ros2_demo_package`

#### Launch Files

##### [`ros2_demo_node_launch.py`](ros2_demo_package/launch/ros2_demo_node_launch.py)

| Argument | Default | Description |
| --- | --- | --- |
| `input_topic` | `~/input` |  |
| `output_topic` | `~/output` |  |
| `name` | `ros2_demo_node` | node name |
| `namespace` | `` | node namespace |
| `params` | `os.path.join(get_package_share_directory("ros2_demo_package"), "config", "params.yml")` | path to parameter file |
| `log_level` | `info` | ROS logging level (debug, info, warn, error, fatal) |
| `use_sim_time` | `false` | use simulation clock |

#### `ros2_demo_node`

##### Subscribed Topics

| Topic | Type | Description |
| --- | --- | --- |
| `~/input` | `geometry_msgs/msg/PointStamped` | |

##### Published Topics

| Topic | Type | Description |
| --- | --- | --- |
| `~/output` | `geometry_msgs/msg/PointStamped` | |

##### Actions

| Action | Type | Description |
| --- | --- | --- |
| `~/action` | `ros2_demo_package_interfaces/action/Fibonacci` | |

##### Parameters

| Parameter | Type | Default | Description |
| --- | --- | --- | --- |
| `param` | `float` | `1.0` | TODO |


## Acknowledgements

This work is accomplished within the projects TODO (FKZ TODO). We acknowledge the financial support by the 🇩🇪 Federal Ministry of Research, Technology and Space (BMFTR).
