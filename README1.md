# YUV Player -- A YUV player based on MFC
## Project
VS2010 MFC project, ref YUV Player Deluxe.

## Project Feature
* support different YUV format.
* support common resolution, support custom width&height, and can add to the system.
* support different rate, loop play.
* support play frame by frame, jump to first frame and last frame.
* window scale.
* support save to yuv file and bmp file.
* support yuv format:
  * y, ie: YUV400.
  * YUV420 planar, ie: YUV420(I420), YV12.
  * YUV422 planar, ie: YUV422(I422), YV16.
  * YUV444 planar, ie: YUV444.
  * YUV422 interleaved, ie: YUY2(YUYV), YVYU, UYVY, VYUY.
  * YUV420 semi-planar, ie: NV12(YUV420SP), NV21.
  * YUV420 semi-planar, ie: NV16(YUV422SP), NV61.
  * RGB24, BGR24.

## Usage
Click menu File->Open option, or drag file to the main window, <br>

## Window view
Setting window: <br>
![Setting](https://github.com/latelee/YUVPlayer/blob/master/screenshots/yuvplayer_setting.png)

About windows: <br>
![About](https://github.com/latelee/YUVPlayer/blob/master/screenshots/yuvplayer_about.png)
  
## Changelog
The binary file will locate in release directory. <br>
* v1.0 first version, can play different yuv format. <br>
* v2.0 impletement basic function for a player.<br>
* v4.0 save parameter(Setting->Apply or OK). 
* v4.1 fix some bug.
* v4.2 add play and save for rgb(24 bit) file

## Testing
Only test under Windows 7 64bit OS, and may run on other Windows OS.<br>

## Some bug
Not found yet.

## Protocol
* Copyright [CST studio Late Lee](http://www.latelee.org)
* Total code is BSP.
* You can use the code for study, and commercial purposes, but give no guarantee.

## TODOs
* split yuv file for Y, U, V.
* support different yuv format transformation. 

## Author
CST studio Late Lee<br>
[CST studio](http://www.latelee.org) <br>
[Donate the author](http://www.latelee.org/donate)

# YUV Player -- ����MFC�����YUV������

## ����˵��
VS2010 MFC���̣�����ο�YUV Player Deluxe���

## ����
* �ɲ��Ÿ��ָ�ʽ��YUV�ļ���
* Ĭ��Ԥ�������ֱ��ʣ�ͬʱ֧���Զ���߿��������ϵͳ��
* ֧�ֲ�ͬ֡�ʲ��ţ�֧��ѭ�����š�
* ֧��ǰ����֡��ת��֧����ת��֡��β֡��
* ֧�ִ������š�
* ֧�ֱ���YUV�ļ���BMPͼƬ�ļ���
* �Զ������ļ������õ��ֱ��ʡ�YUV��ʽ��
* Ŀǰ֧�ָ�ʽ�У�
    * Y���ȷ�������YUV400;
    * YUV420ƽ���ʽ��YUV420(I420);YV12;
    * YYUV422ƽ���ʽ��YUV422(I422);YV16;
    * YUV444��ʽ��YUV444;
    * YUV422��֯��ʽ��YUY2(YUYV);YVYU;UYVY;VYUY;
    * YUV420��ƽ���ʽ��NV12(YUV420SP);NV21;
    * YUV422��ƽ���ʽ��NV16(YUV422SP);NV61;
    * RGB24��BGR24��ʽ

## �÷�
�Ҽ�Openѡ��˵�File->Openѡ�ֱ����ҷ�ļ����������档

## ����
�������ý��棺<br>
![Setting](https://github.com/latelee/YUVPlayer/blob/master/screenshots/yuvplayer_setting.png)

���ڽ��棺<br>
![About](https://github.com/latelee/YUVPlayer/blob/master/screenshots/yuvplayer_about.png)
  
## �汾���
����õĹ���λ��releaseĿ¼�С�<br>
* v1.0 ��ʱ�汾��֧�ָ����ʽ�Ĳ��ţ����ð汾�����߳��Ρ�
* v2.0 �߱��������������ܡ�δ��Ӳ������湦�ܡ�
* v4.0 �߱��������������ܡ��߱��������湦��(��Setting������Apply��OK�ſ���Ч)��֧������Զ���ֱ��ʡ�
* v4.1 bug fix��
* v4.2 ���rgb(24λ)�ļ����š����湦�ܡ�

## ����
�����߽���Windows 7 64bit����ϵͳ�����в���ͨ������������Ӧ�ÿ���������Windowsϵ��ϵͳ�����С�<br>

## ����Ǳ������
���޷��֡�

## Э��
* ��Ȩ���� [��˼�ù����� ���](http://www.latelee.org)
* ������Դ��ʹ��Э�飺BSP��
* ������ѧϰ�о�֮Ŀ�ģ�Ҳ��������ҵĿ�ģ���������֤��������ȫ�ɿ���

## �����ƹ���
* ���YUV�������빦�ܡ�
* ����YUV��ʽ�໥ת�����ܡ�

## ����
˼�ù����� ���<br>
[��˼�ù�����](http://www.latelee.org) <br>
[��ӭ����֧������](http://www.latelee.org/donate)