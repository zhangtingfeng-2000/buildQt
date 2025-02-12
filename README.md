# buildQt 从源代码自动构建Qt

## 说明
1. 本项目的主要目的是从源代码构建Qt的二进制版本(使用GithubActions自动构建)
2. 主要针对开源版本的Qt5、Qt6版本
3. 主要构建Windows版本(使用MSVC、MinGW64、LLVM-MinGW三大编译器)
4. 主要构建static版本
5. 主要构建Release版本

## 版本
1. 无"RP"版本：从Qt完整源代码构建，构建绝大部分组件
2. 有"RP"版本：从Qt组件源代码构建，目前只构建qtbase、qttools、qttranslations、qtsvg共4个组件

## 仓库地址
1. Github: https://github.com/yuanpeirong/buildQt

## 目前已开放版本
1. Qt6 msvc2022_64
2. Qt6 msvc2022_64_RP
3. Qt6 MinGW64
4. Qt6 MinGW64_RP
5. Qt6 LLVM-MinGW编译器版本、Qt5所有版本正在测试中，完成后上传