add_library(QProgressIndicator QProgressIndicator.h QProgressIndicator.cpp)
target_link_libraries(QProgressIndicator Qt5::Widgets)
target_include_directories(QProgressIndicator
  INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}
  )
