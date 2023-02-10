
wiringPi README
---

Please note that the official way to get wiringPi is via git from
git.drogon.net and not GitHub.

ie.

  git clone git://git.drogon.net/wiringPi

The version of wiringPi held on GitHub by "Gadgetoid" is used to build the
wiringPython, Ruby, Perl, etc. wrappers for these other languages. This
version may lag the official Drogon release.  Pull requests may not be
accepted to Github....

Please see

  http://wiringpi.com/

for the official documentation, etc. and the best way to submit bug reports, etc.
is by sending an email to projects@drogon.net

Thanks!

  -Gordon

### Tips:

  1. Please remove other versions of the wiringPi first.
  2. As for Armbian system, you need to update board.sh script file:
     * **BPI-M2Berry**: `echo "BOARD=bpi-m2u" > /var/lib/bananapi/board.sh`
     * **BPI-M2+**: `echo "BOARD=bpi-m2p" > /var/lib/bananapi/board.sh`
---


请注意，获取wiringPi的官方途径是从git.drogon.net克隆而不是GitHub。

例如：

  git clone git://git.drogon.net/wiringPi

Gadgetoid发布的wiringPi版本用于包装wiringPython，Ruby，Perl等其他语言。
该版本可能滞后于官方Drogon版本。在Github中Pull请求可能不被准许。

官方文档参考链接：http://wiringpi.com/

如果您想提交bug报告请发邮件到：projects@drogon.net

感谢！

  -Gordon

### 提示：
  1. 在使用该版本前请先将其他版本的wiringPi移除干净。
  2. 如果您使用的是Armbian系统，您需要修改board.sh脚本文件：
     * **BPI-M2Berry**: `echo "BOARD=bpi-m2u" > /var/lib/bananapi/board.sh`
     * **BPI-M2+**: `echo "BOARD=bpi-m2p" > /var/lib/bananapi/board.sh`
