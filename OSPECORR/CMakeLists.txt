CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
PROJECT(OSPECORR)

LIST(APPEND CMAKE_MODULE_PATH $ENV{MOBICOM_PROJECT_PATH}/common/scripts/cmake)

INCLUDE_DIRECTORIES(../common/scl/src)

ADD_SUBDIRECTORY(common)
ADD_SUBDIRECTORY(components)
