cmake_minimum_required( VERSION 3.23 )
project( ESPBasicMqtt )

set( CMAKE_CXX_STANDARD 14 )

add_executable( ESPBasicMqtt
		ESPBasicMqtt.ino privateInfo.h )

set_target_properties( ESPBasicMqtt PROPERTIES LINKER_LANGUAGE CXX )
