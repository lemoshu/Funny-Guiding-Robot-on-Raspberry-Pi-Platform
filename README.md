# Funny-Guiding-Robot-on-Raspberry-Pi-Platform
*利用树莓派实现一个有趣的迎宾机器人  
*Using Raspberry Pi2 to realize a funny guiding robot 
*实现功能：人脸检测->摇头点头进行迎客->播放欢迎语音(三段不同)->跳舞->下一个客人迎宾，三个后一直播放《学猫叫》
## 使用指南  
1)下载整个文件包  
2)在树莓派上装好Picamere,opencv,pygame等库(具体看代码import处)，注意确保自己有连接RPi的摄像头  
3)连接蓝牙音响(注意：在Alphabot2-pi上可能直接播放音乐虽然连接上了也没声音，最好用pygame的music.mixer模块播放/暂停等)  
4)在python2.7下运行final.py文件即可  
## mp3文件说明
1)1.mp3为《学猫叫》  
2)lisinan.mp3为对一个胖胖的队友的欢迎光临，询问他吃饭了吗  
3)zhangxiao.mp3为对一个美女队友的迎接和赞美  
## 致谢  
此为我在THU读研究生课程《互联网思维》的其中一个课程设计，感谢助教提供的蓝牙音箱以及帮我们找更换的坏零件，以及感谢一起debug的队友(涉及到硬件真的太多bug了，一堆接口、摄像头等问题)
