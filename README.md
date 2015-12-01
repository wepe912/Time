# Time
#some thing about ntp or ntp-s
#let's start
ubuntu server 14
下载：
官网上要key
可以去这里下载
http://sourceforge.net/projects/gsoap2/files/
安装：
http://www.genivia.com/downloads.html#Installing_gSOAP_on_Unix/Linux
上面这个链接是官网的，安装过程中可能出错
收下链接是网友的能够成功安装
http://www.cnblogs.com/coveted/p/3492342.html
总结安装步骤：
1. unzip gsoap_2.8.17.zip
2.确保已经安装了以下这些东西
--------------------------------------------------------
 But if the above fails, then please verify that you have:

	1. Automake tools installed (make and GNU m4)

	2. Bison from www.gnu.org/software/bison or Yacc

	3. Flex from flex.sourceforge.net

	4. OpenSSL from www.openssl.org or GNUTLS from www.gnu.org/software/gnutls or you must disable SSL


Having trouble with automake, Bison, or Flex? See instructions below.
     5. 网上还说要安装openssl的库文件 : sudo apt-get install libssl-dev
    6. sudo apt-get install libgtk2.0-dev libglib2.0-dev （这个不知道需要不，先装上）
-------------------------------------------------------------------------
3.  ./configure
4.make
5.make install
