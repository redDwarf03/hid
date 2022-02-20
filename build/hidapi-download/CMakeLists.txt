# Distributed under the OSI-approved MIT License.  See accompanying
# file LICENSE or https://github.com/Crascit/DownloadProject for details.

cmake_minimum_required(VERSION 3.10)

project(hidapi-download NONE)

include(ExternalProject)
ExternalProject_Add(hidapi-download
                    URL;https://github.com/libusb/hidapi/archive/refs/tags/hidapi-0.11.2.zip
                    SOURCE_DIR          "/Users/reddwarf/SSe/app/LEDGER/hid/build/hidapi-src"
                    BINARY_DIR          "/Users/reddwarf/SSe/app/LEDGER/hid/build/hidapi-build"
                    CONFIGURE_COMMAND   ""
                    BUILD_COMMAND       ""
                    INSTALL_COMMAND     ""
                    TEST_COMMAND        ""
)
