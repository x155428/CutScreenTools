# CutScreenTools
工作中常需要扫描微信发送过来的二维码或者远程别人电脑时需要扫描二维码并复制粘贴扫描的结果，碰巧遇到了javafx的可视化，一时兴起尝试一下自己写一个辅助（没有鸟用）的工具。
该程序没有规划，想到哪写到哪，代码结构很乱。
第一次编程，代码很烂，bug巨多，但是好在写了很多注释，能凑合看。
第一次用git和idea，折腾了很久，还是不太会用，看到上传垃圾文件请勿怪。
环境：idea+openjdk20+javafx(最新的依赖包）
坑：jdk20没有内置javafx，需要引入javafx依赖包，并且运行配置中还要加入vm参数--module-path "D:\idea\openjfx-20_windows-x64_bin-sdk\javafx-sdk-20\lib" --add-modules javafx.controls,javafx.fxml（javafx依赖路径根据情况改） 

运行截图（功能没完善，目前只完成了部分截图功能）：
![图片](https://user-images.githubusercontent.com/83338415/232976489-8f66ef4d-1732-4c1d-bef1-5a9720c57ba5.png)

![图片](https://user-images.githubusercontent.com/83338415/232976937-b25f7757-789b-44c6-ba83-d09cf3039ef5.png)

代码中有些fxml没用，是写界面时打的草稿，请忽略。
想写类似微信的全局快捷键，但是没查到解决办法，查到好像有一个第三方的包可以，但是只能jdk8，就没试，有会的可以告诉我。
