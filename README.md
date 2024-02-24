# CutScreenTools
辅助工作写的工具
自己设计的，该程序没有规划，想到哪写到哪（遇到需求随时加），代码结构比较乱，但是好在写了很多注释，能凑合看。
环境：idea+openjdk20+javafx(最新的依赖包）
坑：jdk20没有内置javafx，需要引入javafx依赖包，并且运行配置中还要加入vm参数--module-path "D:\idea\openjfx-20_windows-x64_bin-sdk\javafx-sdk-20\lib" --add-modules javafx.controls,javafx.fxml（javafx依赖路径根据情况改） 

javafx打包成exe很麻烦，而且打包不适合我随时添加功能并随时能使用，我自己精简了jdk,已经是最小了，运行必要，再小无法运行。
运行截图（主要针对工作中扫描设备激活码，录入授权码写的，不通用，因为客户截图清晰度不一，为了提高识别率，二维码识别增加了二值化，打算转灰度图但是测试下来效果不行）：
![图片](https://user-images.githubusercontent.com/83338415/232976489-8f66ef4d-1732-4c1d-bef1-5a9720c57ba5.png)

![图片](https://user-images.githubusercontent.com/83338415/232976937-b25f7757-789b-44c6-ba83-d09cf3039ef5.png)
字符处理是针对安全设备的日志写的一些格式化的东西（平台没做格式化)，方便分析安全事件，有针对性，不通用，只是工作中需要用到。代码中尝试用了一些数据结构，也算是一种练习。
![图片](https://github.com/x155428/CutScreenTools/assets/83338415/678df1b0-5cd3-4c18-95c1-b7d4f5fd292f)

代码中有些fxml没用，是写界面时打的草稿，请忽略。
想写类似微信的全局快捷键，但是没查到解决办法，查到好像有一个第三方的包可以，但是只能jdk8就没试。
