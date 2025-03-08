include_guard(GLOBAL)
cmake_minimum_required(VERSION 3.19 FATAL_ERROR)
project("templatelists")
# Function
function(templatelists)
	message(STATUS "Hello world!")
endfunction()
# Test
if(NOT PROJECT_IS_TOP_LEVEL)
	return()
endif()
templatelists()
