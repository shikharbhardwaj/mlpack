set(SOURCES
  no_decay.hpp
)

set(DIR_SRCS)
foreach(file ${SOURCES})
  set(DIR_SRCS ${DIR_SRCS} ${CMAKE_CURRENT_SOURCE_DIR}/${file})
endforeach()

set(MLPACK_SRCS ${MLPACK_SRCS} ${DIR_SRCS} PARENT_SCOPE)
