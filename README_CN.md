KBEngine_unity3d_demo
=============

##����Ŀ��ΪKBEngine���������Ŀͻ�����ʾ��д
http://www.kbengine.org

##�ٷ���̳

	http://bbs.kbengine.org


##QQ����Ⱥ

	461368412


##Releases

	sources		: https://github.com/kbengine/kbengine_unity3d_demo/releases/latest
	binarys		: https://sourceforge.net/projects/kbengine/files/


##KBE����ĵ�

	https://github.com/kbengine/kbengine_unity3d_plugins/blob/master/README.md


##��ʼ:
	1. ȷ���Ѿ����ع�KBEngine��������棬���û��������������
		���ط����Դ��(KBEngine)��
			https://github.com/kbengine/kbengine/releases/latest

		����(KBEngine)��
			http://www.kbengine.org/docs/build.html

		��װ(KBEngine)��
			http://www.kbengine.org/docs/installation.html

	2. ����kbengine�ͻ��˲��������Demo�ʲ���:

	    * ʹ��git�����У����뵽kbengine_unity3d_demoĿ¼ִ�У�

	        git submodule update --init --remote
![submodule_update1](http://www.kbengine.org/assets/img/screenshots/gitbash_submodule.png)

		* ����ʹ�� TortoiseGit(ѡ��˵�): TortoiseGit -> Submodule Update:
![submodule_update2](http://www.kbengine.org/assets/img/screenshots/unity3d_plugins_submodule_update.jpg)

                * Ҳ�����ֶ�����kbengine�ͻ��˲��������Demo�ʲ���

		        �ͻ��˲�����أ�
		            https://github.com/kbengine/kbengine_unity3d_plugins/releases/latest
		            ���غ��뽫���ѹ�������Դ���������: Assets/plugins/kbengine/kbengine_unity3d_plugins

		        ������ʲ������أ�
		            https://github.com/kbengine/kbengine_demos_assets/releases/latest
		            ���غ��뽫���ѹ��,����Ŀ¼�ļ������ڷ���������Ŀ¼"kbengine/"֮�£�����ͼ��

	3. ����������ʲ���"kbengine_demos_assets"������������Ŀ¼"kbengine/"֮�£�����ͼ��
![demo_configure](http://www.kbengine.org/assets/img/screenshots/demo_copy_kbengine.jpg)


##����Demo(��ѡ):

	�ı��¼IP��ַ��˿ڣ�ע�⣺���ڷ���˶˿ڲ��ֲο�http://www.kbengine.org/cn/docs/installation.html��:
![demo_configure](http://www.kbengine.org/assets/img/screenshots/demo_configure.jpg)

		kbengine_unity3d_demo\Scripts\kbe_scripts\clientapp.cs -> ip
		kbengine_unity3d_demo\Scripts\kbe_scripts\clientapp.cs -> port


##����������:

	ȷ����kbengine_unity3d_demo\kbengine_demos_assets���Ѿ�������KBEngine��Ŀ¼��
		�ο��Ϸ��½ڣ���ʼ

	ʹ�������ű���������ˣ�
		Windows:
			kbengine\kbengine_demos_assets\start_server.bat

		Linux:
			kbengine\kbengine_demos_assets\start_server.sh

	�������״̬��
			��������ɹ���������־���ҵ�"Components::process(): Found all the components!"��
			�κ��������������־������"ERROR"�ؼ��֣����ݴ����������Խ����
			(����ο�: http://www.kbengine.org/docs/startup_shutdown.html)


##�����ͻ���:

	ֱ����Unity3D�༭���������߱��������
	������ͻ��ˣ�Unity Editor -> File -> Build Settings -> PC, MAC & Linux Standalone.��


##���ɵ�������(��ѡ):
	
	�����ʹ��Recastnavigation��3D����Ѱ·��recastnavigation���ɵĵ�������Navmeshs�������ڣ�
		kbengine\kbengine_demos_assets\res\spaces\*

	��Unity3D��ʹ�ò�����ɵ�������Navmeshs��:
		https://github.com/kbengine/unity3d_nav_critterai


##�ṹ�����壺

	KBE�����U3D�ͷ�����֮��Ĺ�ϵ��
		������������������������֮���������Ϣ�����˺ŵ�½/�ǳ����̡��ɷ����֪ͨ�����������߼�ʵ�塢ά��ͬ�����߼�ʵ���������ݵȵȡ�
		�����U3D�������ĳЩ�¼�������U3Dͼ�β㣬ͼ�β�����Ƿ���Ҫ����ĳЩ�¼�������ݽ�����Ⱦ���֣����磺�������ĳ��NPC���ƶ��ٶ����ӡ�HP�仯����
			U3Dͼ�β㽫�����¼�����������㣨���磺����ƶ��ˡ�����˸��ťUI��������߼��ű�������Ƿ���Ҫ��ת���������ȵȡ�

	Plugins\kbengine\kbengine_unity3d_plugins��
		KBE�ͻ��˲���ĺ��Ĳ���롣

	Scripts\kbe_scripts��
		KBE�ͻ��˵��߼��ű����ڴ�ʵ�ֶ�Ӧ����˵�ʵ��ű���ʵ��ı������ݽṹ�����ܿͻ����жϵȣ���

		Scripts\kbe_scripts\Account.cs��
			��ӦKBE����˵��˺�ʵ��Ŀͻ��˲��֡�

		Scripts\kbe_scripts\Avatar.cs��
			��ӦKBE����˵�����Ϸ�����ʵ��Ŀͻ��˲��֡�

		Scripts\kbe_scripts\Monster.cs��
			��ӦKBE����˵Ĺ���ʵ��Ŀͻ��˲��֡�

		Scripts\kbe_scripts\clientapp.cs��
			��KBE����ϵ�г����һ���ͻ���APP�����а���KBE�ͻ��˲���ĳ�ʼ�������ٵȵȡ�

		Scripts\kbe_scripts\interfaces��
			��ӦKBE��entity_defs\interfaces����������ģ�顣

	Scripts\u3d_scripts��
		Unity3Dͼ�β㣨����������Ⱦ��UI�����岿��������ģ�͡�����ģ�͡�һ�й�����ʾ�Ķ����ȵȣ���

		Scripts\u3d_scripts\GameEntity.cs��
			�����ǹ��ﻹ����Ҷ��ɴ˽ű�����ģ�Ͷ����ȱ��ֲ��֡�

		Scripts\u3d_scripts\World.cs:
			������Ϸ�д��ͼ�򸱱�����Ⱦ��ű������磺���𽫾����3D���ﴴ���������С�

		Scripts\u3d_scripts\UI.cs:
			ά����Ϸ��UI����ű���

	Scenes\start.unity:
		��ʼ�������ɴ�����������Ϸ��

	Scenes\_scenes\login.unity:
		��½������

	Scenes\_scenes\selavatars.unity:
		��ɫѡȡ������

	Scenes\_scenes\world.unity:
		��Ϸ�д��ͼ/����������

##��ʾ��ͼ:
![screenshots1](http://www.kbengine.org/assets/img/screenshots/unity3d_demo9.jpg)
![screenshots2](http://www.kbengine.org/assets/img/screenshots/unity3d_demo10.jpg)
![screenshots3](http://www.kbengine.org/assets/img/screenshots/unity3d_demo11.jpg)
