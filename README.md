# test_params_pkg


` ros2 run test_params_pkg test_params_node --ros-args -p declared_parameter:="Totally" `


## OUTPUT:

`

terminate called after throwing an instance of 'rclcpp::exceptions::ParameterAlreadyDeclaredException'
  what():  parameter 'declared_parameter' has already been declared

`



