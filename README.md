# cvf-p.e
CVF Encryption基于以AES算法进行加密，其伪加密仅用于处理加密后的文件，使其无法正常使用相关识别。  
本程序内置附带实加密程序，实现真正的文件加密，本程序原理只是为加密文件再次进行更改相关编码以使其它程序无法识别。  
本程序最初用于本人备份特殊文件防止云端检测而制作。  
本程序内置UUID生成工具及UUID修复工具，用于修改文件名。  
本程序暂未制作UI版，程序基于批处理命令行运行，唯一显示的窗口即cmd窗口。  

下载链接1：https://www.123pan.com/s/bYVA-myYoA.html  
下载链接2：https://vnkus.lanzouo.com/b02qevrxe  
下载链接3：  

如果指向下载的链接附有密码，密码为  

	cvfa  

# cvf-setup_info  
=- 前言 -=  
欢迎安装CVF P.Encryption  
此软件为免费软件，不得用于任何盈利项目。  
此软件原理非常简单，仅供个人加密使用。  
如有专业用途需要，请使用专业加密软件。  
如非法使用本软件的，一切后果由使用者承担。  
	
=- 提示 -=  
此版本为公测版第二代版本，如有任何问题，请及时联系本人。  
已初步键入管理员权限继承，但部分设备可能无法生效。  
请不要将软件安装到C盘，否则会被系统限制部分功能。  
初步项目，未制作UI和全局变量，逐步完善注册表关联。  
相对于上一版本，重构优化了运行速度及运行逻辑。  
更多内容敬请期待......  
	
	请不要将软件安装到C盘！  
	请不要将软件安装到C盘！！  
	请不要将软件安装到C盘！！！  
	
禁止删除组件库文件，否则相关功能会因为缺少组件库而无法使用。  

	seer文件为基础数据组件库。  
	sper文件为基础程序组件库。  
	spxr文件为扩展程序组件库。 
	
其中，基础组件为安装程序附带，扩展组件需要自行下载安装。  
此安装程序内附带1套15件基础的sper组件。  
如需要更多的扩展组件，请前往蔚蓝空间获取更多的信息。  
	
=- 构建 -=  
制作：Vnkus Lande  
发行：Eyvnxi Studio Team.  
版本：v2.1.3  
内部版本：23.2.1.03  
详情文档：https://docs.qq.com/doc/DZW9DZGtLZllpU29L  
第三方下载：https://www.123pan.com/s/bYVA-myYoA.html  
GitHub：https://github.com/Lande1srt/cvf-p.e  
蔚蓝空间：http://tanmvnku.ysepan.com  
E-mail：vnkus.lande@outlook.com  
Tencnet QQ：[309483098  ](https://qm.qq.com/cgi-bin/qm/qr?k=mXLPE5aidmDGmqfHNM9vw9GwB_Yj4QU8)  
	
=- 安全 -=  
请确认此安装程序属性是否带有数字签名。  
如果此安装程序属性带有数字签名，请对比序列号及其他信息。  
数字签名证书序列号：3fce59d7186e098e43afec27a95494cc  
数字签名证书指纹：33bd83800f97cec282e58ff1645f454f9acd0c28  
数字签名证书公钥：30 81 89 02 81 81 00 e3 1b 96 20 b4 92 0e 69 43 4d 65 50 77 97 8e 69 93 ce 32 54 3c ae 1a 69 7c a7 0a f4 22 be d1 19 4e db 1a a6 f9 98 0d 73 13 1c 7e 9d 16 a9 fc 0f 63 14 36 6f 99 e4 d5 08 d3 24 15 98 5b e3 25 26 97 5b c6 85 41 dc 30 5a 9b 7e c9 ad 5c 8e 77 db 86 9b ea fc ad da f5 ba cd bf 7b 8b f3 8a 0e d1 1c 07 0e 88 30 fb 3d 54 24 59 22 0b 32 d0 0a 0c b4 02 2d 64 4b 7c 91 92 a2 c7 30 e9 31 7b 89 a1 02 03 01 00 01  
	
=- 组件 -= =- 基础包 -=

	CVF Start.exe		--> CVF启动程序  
	CVF Work.exe		--> 打开CVF安装路径程序  
	Unenc.exe		--> 安装Encryptofor程序  
	cvfa.exe		--> 伪加密编码程序  
	cvfenccore.sper		--> 基础加密控制组件  
	cvfunenccore.sper	--> 基础解密控制组件  
	cvfilesenc.sper		--> 基础文件加密组件  
	cvfilesunenc.sper	--> 基础文件解密组件  
	cvfaudioenc.sper	--> 基础音频加密组件  
	cvfaudiounenc.sper	--> 基础音频解密组件  
	cvfvideoenc.sper	--> 基础视频加密组件  
	cvfvideounenc.sper	--> 基础视频解密组件  
	cvfencinf.sper		--> 实加密程序信息组件  
	cvflandetq.sper		--> 以Edge定制QQ组件  
	cvfonlinedoc.sper	--> 以Edge定制文档组件  
	cvfruncore.sper 	--> CVF核心控制组件  
	cvfrunoutinfo.sper	--> CVF信息控制组件  
	cvfuidfactory.sper	--> UUID工具组件  
	cvfuidrepair.sper	--> UUID命名修复组件  
	coredata.seer		--> 基础逻辑代码数据  
	lfencforw.seer		--> Encrypto安装程序数据  
	cvfilerunenc.sper	-x> [已废弃的控制组件]  

=- 组件 -= =- 扩展包 -=  

	cvfilesenc-pro.spxr	--> 高级文件加密组件  
	cvfautowebset.spxr	--> 自动化Web API设定  
	
	
	
更多信息敬请期待......  
2023.04.23	12:36	Vnkus Lande Editon  
  
  
  
  # cvf-简要使用说明
  本程序安装完成后会在桌面创建一个名为CVF P.Encryption的快捷方式，双击打开CVF的安装页面。  
因为本程序暂未编写关联程序的注册表项，所以文件加密解密都将先复制于程序安装目录。  
双击CVF Start.exe运行程序，然后键入1获取Encryption实加密程序。（如果安装程序向导已启动解密程序且您已安装可跳过此步骤。）  
	
此文件来源于：https://macpaw.com/encrypto  
保证版本更新可自行下载，但基本不会频繁更新（内置Win7UI即可证明）  
建议使用内置版本。  
安装Encryption时请勿更改安装路径。  
然后使用Encryption程序进行文件加密（可选择文件右键使用）。  
将加密后的cryption文件拷贝至CVF安装路径内即可。  
然后再双击CVF Start.exe运行程序选择选项即可。  
	
运行程序时部分组件会创建CVF_RunOutput_Files文件夹于程序安装目录。  
完成操作后如有需要输出的文件将存放于程序安装目录CVF_RunOutput_Files下。  
	
