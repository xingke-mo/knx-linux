#Generated by VisualGDB project wizard.
#Note: VisualGDB will automatically update this file when you add new sources to the project.

cmake_minimum_required(VERSION 2.7)
project(knx-linux)
set(LIBRARIES_FROM_REFERENCES "")
add_executable(knx-linux knx/address_table_object.cpp knx/apdu.cpp knx/application_layer.cpp knx/application_program_object.cpp knx/association_table_object.cpp knx/bau.cpp knx/bau57B0.cpp knx/bits.cpp knx/cemi_frame.cpp knx/data_link_layer.cpp knx/datapoint_types.cpp knx/device_object.cpp knx/group_object.cpp knx/group_object_table_object.cpp knx/interface_object.cpp knx/ip_parameter_object.cpp knx/memory.cpp knx/network_layer.cpp knx/npdu.cpp knx/table_object.cpp knx/tpdu.cpp knx/transport_layer.cpp main.cpp linux_platform.cpp)
target_link_libraries(knx-linux "${LIBRARIES_FROM_REFERENCES}")
set(CMAKE_C_FLAGS_DEBUG "${CMAKE_C_FLAGS_DEBUG} -Wall -Wno-unknown-pragmas -Wno-switch")
set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -Wall -Wno-unknown-pragmas -Wno-switch")
include_directories(/usr/include/x86_64-linux-gnu)
