# 包含公共库
include_directories(${CMAKE_SOURCE_DIR}/Status)

# 生成可执行文件
add_executable(05.28-05.29 StringUtil.h StringUtil.c MPList.h MPList.c 05.28-05.29.c)
# 链接公共库
target_link_libraries(05.28-05.29 Scanf_lib)