# vscode_ansi_c_debug_config
visual studio code 调试c语言配置

  1. 调试时，需要事先在项目目录 mkdir bin 目录
  2. 然后复制clone回去的vscode_c目录下的所有文件到项目根目录隐藏文件夹内 -> .vscode
  3. 现在，生成二进制文件，设置断点，然后f5开始调试吧
  4. 如果不需要git管理bin目录下生成的二进制文件，可以在全局gitignore或者 针对项目的gitignore中 设置忽略bin目录即可
  5. vscode_c 目录下有个 rtf文件， macos自带的文本编辑器写的，其他编辑器打开会乱码，无碍使用，里面是一个简单的使用教程

Note: 适用于macos系统下，vscode更新频繁，对调试的配置项在未来可能会不同且本仓库可能不及时更新，如果失效，请浏览改url
https://code.visualstudio.com/docs/cpp/cpp-debug，获取最新的，根据url中的步骤，一步一步走下来就可以得到一个简单的
调试配置文件

  
