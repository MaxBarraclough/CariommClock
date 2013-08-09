cmake_minimum_required(VERSION 2.8.7)
## Quite likely works on earlier versions, but we get a warning if we omit this.
## Build was tested on 2.8.7 in Xubuntu GNU/Linux.


project(clock)

find_package(PkgConfig)

pkg_check_modules(GTKMM gtkmm-3.0) # look into FindPkgConfig.cmake, 
                                                                # it contains documentation
# Now the variables GTKMM_INCLUDE_DIRS, GTKMM_LIBRARY_DIRS and GTKMM_LIBRARIES 
# contain what you expect 

add_subdirectory(src_dir) 

