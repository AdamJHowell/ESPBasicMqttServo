cmake_minimum_required( VERSION 3.23 )
project( ESPBasicMqttServo )

set( CMAKE_CXX_STANDARD 14 )

add_executable( ESPBasicMqttServo
		ESPBasicMqttServo.ino
		privateInfo.h )

set_target_properties( ESPBasicMqttServo PROPERTIES LINKER_LANGUAGE CXX )
