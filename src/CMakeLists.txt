INCLUDE_DIRECTORIES(../lib ../include)
set(HEADERS ../lib/tinyxml2.h)
set(PREPROCESS_SRC preprocess.cc)
ADD_EXECUTABLE(PreProcess ${PREPROCESS_SRC})
TARGET_LINK_LIBRARIES(PreProcess tinyxml2 z)