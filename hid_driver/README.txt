����xdisp_virt��Ӧ��HID����������������

��װ��
�����Ӧ64λ����32λϵͳ��Ŀ¼�У����� install.bat ִ�а�װ��
��װ�ɹ��󣬻����豸�������г��� ��Fanxiushu Virtual HID Input Device���� HID�豸��
��ͬʱ����һ�� HID���̺�����HID��꣨������;�����꣩��

��װ�ɹ������� xdisp_virt.exe���򣬾ͻ��Զ�ʹ���������̺����������Ӧ�ò��ģ�����롣

ж�أ�
�����Ӧ��Ŀ¼������ uninstall.batִ������ж�أ�ж��ǰ��ȷ�� xdisp_virt.exe�������С�

����û��ǩ����Ҫ��ȷ��64λϵͳ��װ����Ҫ���Լ�ǩ����������ϵͳ�����ڡ���ֹ����ǿ��ǩ����ģʽ��

����ΪĳЩ��Ϸ�޷�ʹ��Ӧ�ò��������ģ�����ӵ�������
��ͨԶ�̿���ͬ������ʹ�ñ�����.

*******************************************************************
����HID������������ڶ���ʾ���µ�����������
�ڶ���ʾ�������£�WIN7, WIN8, WIN10 1511 ������ϵͳ�У�HID�������Ĭ��ֻʶ������ʾ����
mouse_patch.sys ��������������˴����⣬ʹ��HID���������ʶ��������ʾ����
�ڰ�װ�ɹ��������������������֮������ install_mouse_patch.bat��װ��

fanxiushu 2019-04-29 06-30

=========================================
This is the HID virtual mouse and keyboard driver for xdisp_virt.

installation:
Go to the directory corresponding to the 64-bit or 32-bit system and run install.bat to perform the installation.
After the installation is successful, the HID device of ��Fanxiushu Virtual HID Input Device�� will appear in the device manager.
At the same time, an HID keyboard and two HID mice (relative to the mouse and absolute mouse) are generated.

After the installation is successful, restarting the xdisp_virt.exe program will automatically use the driver keyboard and mouse instead of the application layer's analog input.

Uninstall:
Enter the corresponding directory, run uninstall.bat to perform driver uninstallation, and make sure that xdisp_virt.exe is not running before uninstalling.

The driver does not have a signature. To properly install on a 64-bit system, you need to sign it yourself, or let the system run in the "Forbidden Drive Forced Signature" mode.

This is a driver added for some games that cannot use the application layer's mouse and keyboard emulation.
Ordinary remote control can also use this driver.

************************************************** *****************
Virtual HID absolute mouse coordinates correction patch under multiple monitors:
In a multi-monitor environment, in systems such as WIN7, WIN8, and WIN10 1511, the HID absolute mouse only recognizes the primary display by default.
The mouse_patch.sys mouse filter driver solves this problem, making the HID absolute mouse recognize all displays.
After installing the above virtual mouse and keyboard driver, run install_mouse_patch.bat to install.

fanxiushu 2017-2019
