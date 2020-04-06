# vscode_ansi_c_debug_config
visual studio code 调试c语言配置

  1. 调试时，需要事先在项目目录 mkdir bin 目录
  2. 然后复制clone回去的vscode_c目录下的所有文件到项目根目录隐藏文件 .vscode
  3. 现在，生成二进制文件，设置断点，然后f5开始调试吧
  4. 如果不需要git管理bin目录下生成的二进制文件，可以在全局gitignore或者 针对项目的gitignore中 设置忽略bin目录即可

Note: 适用于macos系统下

  
