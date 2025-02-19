# Create a library called "rail_condition_monitor"
add_library(rail_condition_monitor_lib rail_condition_monitor.cpp)

# Specify include directories for the library
target_include_directories(rail_condition_monitor_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
