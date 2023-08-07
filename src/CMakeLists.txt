aux_source_directory(. SRC_LIST)

ADD_LIBRARY(lib STATIC ${SRC_LIST}) 

ADD_EXECUTABLE(main main.cpp)
TARGET_LINK_LIBRARIES(main lib)