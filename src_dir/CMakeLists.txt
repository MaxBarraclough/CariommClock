link_directories(
    ${GTKMM_LIBRARY_DIRS}  )

include_directories(
    ${GTKMM_INCLUDE_DIRS}  )

add_executable(clock # e.g. the name of the executable on Windows will be clock.exe 
    main.cc
    clock.cc
    clock.h )

target_link_libraries(clock
    ${GTKMM_LIBRARIES}  )

