# opencv_4.5_mingw
`build by mingw` 
全部为x64这么高版本的没什么人用32位吧   
`CmakeLists.txt` 引入方法：   
添加
```cmake
# world 需要指明world模块
set(OpenCV_DIR ./x64/mingw/staticlib)
find_package(OpenCV REQUIRED world)
message(${OpenCV_FOUND})
include_directories(${OpenCV_INCLUDE_DIRS})
target_link_libraries(${your_PROTECT} ${OpenCV_LIBS})
```

- 动态库版本(world):[百度 网盘下载地址](https://pan.baidu.com/s/1Oj7Tpz210JvUX_DjbltDIA)密码：`0gdl`
- 动态库版本(no_world)：[百度网盘下载地址](https://pan.baidu.com/s/1cdN6j5qRdg3oyB1KILrDsg)密码：`mrml`
- 静态库版本（world）：[百度网盘下载地址](https://pan.baidu.com/s/17HLQ2DDD7qILEnZ5MmGI8g)提取码:`7i8d`
- 静态库版本（no_world）:[百度网盘下载地址](https://pan.baidu.com/s/192gk_MznqUN1sGUQ5Fueuw)提取码:`e5t5`
