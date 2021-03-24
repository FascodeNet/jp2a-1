add_executable(jp2a aspect_ratio.c curl.c html.c image.c jp2a.c options.c term.c)
target_link_libraries(jp2a jpeg)