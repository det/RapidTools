add_executable (AddZip AddZip.cpp)
target_link_libraries (AddZip Rapid)

add_executable (BuildSvn BuildSvn.cpp)
target_link_libraries (BuildSvn Rapid)

add_executable (MakeZip MakeZip.cpp)
target_link_libraries (MakeZip Rapid)

add_executable (Streamer Streamer.cpp)
target_link_libraries (Streamer Rapid)
