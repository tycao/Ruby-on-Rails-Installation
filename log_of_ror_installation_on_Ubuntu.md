zogy@ubuntu:~$ ruby -v
程序“ruby”尚未安装。 您可以使用以下命令安装：
sudo apt install ruby
zogy@ubuntu:~$ sudo apt-get install ruby
[sudo] zogy 的密码： 
E: 无法获得锁 /var/lib/dpkg/lock - open (11: 资源暂时不可用)
E: 无法锁定管理目录(/var/lib/dpkg/)，是否有其他进程正占用它？
zogy@ubuntu:~$ sudo rm /var/lib/dpkg/lock 
zogy@ubuntu:~$ sudo apt-get install ruby
正在读取软件包列表... 完成
正在分析软件包的依赖关系树       
正在读取状态信息... 完成       
将会同时安装下列软件：
  fonts-lato libruby2.3 rake ruby-did-you-mean ruby-minitest ruby-net-telnet
  ruby-power-assert ruby-test-unit ruby2.3 rubygems-integration
建议安装：
  ri ruby-dev bundler
下列【新】软件包将被安装：
  fonts-lato libruby2.3 rake ruby ruby-did-you-mean ruby-minitest
  ruby-net-telnet ruby-power-assert ruby-test-unit ruby2.3
  rubygems-integration
升级了 0 个软件包，新安装了 11 个软件包，要卸载 0 个软件包，有 473 个软件包未被升级。
需要下载 5,981 kB 的归档。
解压缩后会消耗 27.0 MB 的额外空间。
您希望继续执行吗？ [Y/n] y
获取:2 http://us.archive.ubuntu.com/ubuntu xenial/main i386 rubygems-integration all 1.10 [4,966 B]
获取:3 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby-did-you-mean all 1.0.0-2 [8,390 B]
获取:1 http://101.44.1.10/files/303900000591EFA4/mirrors.yun-idc.com/ubuntu xenial/main i386 fonts-lato all 2.0-1 [2,693 kB]
获取:4 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby-minitest all 5.8.4-2 [36.6 kB]
获取:5 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby-net-telnet all 0.1.1-2 [12.6 kB]
获取:6 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby-power-assert all 0.2.7-1 [7,668 B]
获取:7 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby-test-unit all 3.1.7-2 [60.3 kB]
获取:8 http://us.archive.ubuntu.com/ubuntu xenial-updates/main i386 libruby2.3 i386 2.3.1-2~16.04 [3,062 kB]
获取:9 http://us.archive.ubuntu.com/ubuntu xenial-updates/main i386 ruby2.3 i386 2.3.1-2~16.04 [41.0 kB]
获取:10 http://us.archive.ubuntu.com/ubuntu xenial/main i386 ruby all 1:2.3.0+1 [5,530 B]
获取:11 http://us.archive.ubuntu.com/ubuntu xenial/main i386 rake all 10.5.0-2 [48.2 kB]
已下载 5,981 kB，耗时 40秒 (149 kB/s)                                          
正在选中未选择的软件包 fonts-lato。
(正在读取数据库 ... 系统当前共安装有 205639 个文件和目录。)
正准备解包 .../fonts-lato_2.0-1_all.deb  ...
正在解包 fonts-lato (2.0-1) ...
正在选中未选择的软件包 rubygems-integration。
正准备解包 .../rubygems-integration_1.10_all.deb  ...
正在解包 rubygems-integration (1.10) ...
正在选中未选择的软件包 ruby-did-you-mean。
正准备解包 .../ruby-did-you-mean_1.0.0-2_all.deb  ...
正在解包 ruby-did-you-mean (1.0.0-2) ...
正在选中未选择的软件包 ruby-minitest。
正准备解包 .../ruby-minitest_5.8.4-2_all.deb  ...
正在解包 ruby-minitest (5.8.4-2) ...
正在选中未选择的软件包 ruby-net-telnet。
正准备解包 .../ruby-net-telnet_0.1.1-2_all.deb  ...
正在解包 ruby-net-telnet (0.1.1-2) ...
正在选中未选择的软件包 ruby-power-assert。
正准备解包 .../ruby-power-assert_0.2.7-1_all.deb  ...
正在解包 ruby-power-assert (0.2.7-1) ...
正在选中未选择的软件包 ruby-test-unit。
正准备解包 .../ruby-test-unit_3.1.7-2_all.deb  ...
正在解包 ruby-test-unit (3.1.7-2) ...
正在选中未选择的软件包 libruby2.3:i386。
正准备解包 .../libruby2.3_2.3.1-2~16.04_i386.deb  ...
正在解包 libruby2.3:i386 (2.3.1-2~16.04) ...
正在选中未选择的软件包 ruby2.3。
正准备解包 .../ruby2.3_2.3.1-2~16.04_i386.deb  ...
正在解包 ruby2.3 (2.3.1-2~16.04) ...
正在选中未选择的软件包 ruby。
正准备解包 .../ruby_1%3a2.3.0+1_all.deb  ...
正在解包 ruby (1:2.3.0+1) ...
正在选中未选择的软件包 rake。
正准备解包 .../archives/rake_10.5.0-2_all.deb  ...
正在解包 rake (10.5.0-2) ...
正在处理用于 fontconfig (2.11.94-0ubuntu1.1) 的触发器 ...
正在处理用于 libc-bin (2.23-0ubuntu3) 的触发器 ...
正在处理用于 man-db (2.7.5-1) 的触发器 ...
正在设置 fonts-lato (2.0-1) ...
正在设置 rubygems-integration (1.10) ...
正在设置 ruby-did-you-mean (1.0.0-2) ...
正在设置 ruby-minitest (5.8.4-2) ...
正在设置 ruby-net-telnet (0.1.1-2) ...
正在设置 ruby-power-assert (0.2.7-1) ...
正在设置 ruby-test-unit (3.1.7-2) ...
正在设置 libruby2.3:i386 (2.3.1-2~16.04) ...
正在设置 ruby2.3 (2.3.1-2~16.04) ...
正在设置 ruby (1:2.3.0+1) ...
正在设置 rake (10.5.0-2) ...
正在处理用于 libc-bin (2.23-0ubuntu3) 的触发器 ...
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ ruby -v
ruby 2.3.1p112 (2016-04-26) [i386-linux-gnu]
zogy@ubuntu:~$ uname
Linux
zogy@ubuntu:~$ uname -a
Linux ubuntu 4.4.0-34-generic #53-Ubuntu SMP Wed Jul 27 16:06:28 UTC 2016 i686 i686 i686 GNU/Linux
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ gem install rails -v 4.1.0
ERROR:  Could not find a valid gem 'rails' (= 4.1.0), here is why:
          Unable to download data from https://rubygems.org/ - SSL_connect returned=1 errno=0 state=error: certificate verify failed (https://api.rubygems.org/specs.4.8.gz)
ERROR:  Possible alternatives: rails
zogy@ubuntu:~$ gem install rails -v 4.1.0
Fetching: rack-1.5.5.gem (100%)
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /var/lib/gems/2.3.0 directory.
zogy@ubuntu:~$ sudo gem install rails -v 4.1.0
Fetching: rack-1.5.5.gem (100%)
Successfully installed rack-1.5.5
Fetching: concurrent-ruby-1.0.5.gem (100%)
Successfully installed concurrent-ruby-1.0.5
Fetching: sprockets-3.7.1.gem (100%)
Successfully installed sprockets-3.7.1
Fetching: erubis-2.7.0.gem (100%)
Successfully installed erubis-2.7.0
Fetching: builder-3.2.3.gem (100%)
Successfully installed builder-3.2.3
Fetching: thread_safe-0.3.6.gem (100%)
Successfully installed thread_safe-0.3.6
Fetching: tzinfo-1.2.3.gem (100%)
Successfully installed tzinfo-1.2.3
Fetching: i18n-0.8.4.gem (100%)
Successfully installed i18n-0.8.4
Fetching: activesupport-4.1.0.gem (100%)
Successfully installed activesupport-4.1.0
Fetching: actionview-4.1.0.gem (100%)
Successfully installed actionview-4.1.0
Fetching: rack-test-0.6.3.gem (100%)
Successfully installed rack-test-0.6.3
Fetching: actionpack-4.1.0.gem (100%)
Successfully installed actionpack-4.1.0
Fetching: sprockets-rails-2.3.3.gem (100%)
Successfully installed sprockets-rails-2.3.3
Fetching: bundler-1.15.1.gem (100%)
Successfully installed bundler-1.15.1
Fetching: thor-0.19.4.gem (100%)
Successfully installed thor-0.19.4
Fetching: railties-4.1.0.gem (100%)
Successfully installed railties-4.1.0
Fetching: mime-types-1.25.1.gem (100%)
Successfully installed mime-types-1.25.1
Fetching: polyglot-0.3.5.gem (100%)
Successfully installed polyglot-0.3.5
Fetching: treetop-1.4.15.gem (100%)
Successfully installed treetop-1.4.15
Fetching: mail-2.5.5.gem (100%)
Successfully installed mail-2.5.5
Fetching: actionmailer-4.1.0.gem (100%)
Successfully installed actionmailer-4.1.0
Fetching: arel-5.0.1.20140414130214.gem (100%)
Successfully installed arel-5.0.1.20140414130214
Fetching: activemodel-4.1.0.gem (100%)
Successfully installed activemodel-4.1.0
Fetching: activerecord-4.1.0.gem (100%)
Successfully installed activerecord-4.1.0
Fetching: rails-4.1.0.gem (100%)
Successfully installed rails-4.1.0
Parsing documentation for rack-1.5.5
Installing ri documentation for rack-1.5.5
Parsing documentation for concurrent-ruby-1.0.5
Installing ri documentation for concurrent-ruby-1.0.5
Parsing documentation for sprockets-3.7.1
Installing ri documentation for sprockets-3.7.1
Parsing documentation for erubis-2.7.0
Installing ri documentation for erubis-2.7.0
Parsing documentation for builder-3.2.3
Installing ri documentation for builder-3.2.3
Parsing documentation for thread_safe-0.3.6
Installing ri documentation for thread_safe-0.3.6
Parsing documentation for tzinfo-1.2.3
Installing ri documentation for tzinfo-1.2.3
Parsing documentation for i18n-0.8.4
Installing ri documentation for i18n-0.8.4
Parsing documentation for activesupport-4.1.0
Installing ri documentation for activesupport-4.1.0
Parsing documentation for actionview-4.1.0
Installing ri documentation for actionview-4.1.0
Parsing documentation for rack-test-0.6.3
Installing ri documentation for rack-test-0.6.3
Parsing documentation for actionpack-4.1.0
Installing ri documentation for actionpack-4.1.0
Parsing documentation for sprockets-rails-2.3.3
Installing ri documentation for sprockets-rails-2.3.3
Parsing documentation for bundler-1.15.1
Installing ri documentation for bundler-1.15.1
Parsing documentation for thor-0.19.4
Installing ri documentation for thor-0.19.4
Parsing documentation for railties-4.1.0
Installing ri documentation for railties-4.1.0
Parsing documentation for mime-types-1.25.1
Installing ri documentation for mime-types-1.25.1
Parsing documentation for polyglot-0.3.5
Installing ri documentation for polyglot-0.3.5
Parsing documentation for treetop-1.4.15
Installing ri documentation for treetop-1.4.15
Parsing documentation for mail-2.5.5
Installing ri documentation for mail-2.5.5
Parsing documentation for actionmailer-4.1.0
Installing ri documentation for actionmailer-4.1.0
Parsing documentation for arel-5.0.1.20140414130214
Installing ri documentation for arel-5.0.1.20140414130214
Parsing documentation for activemodel-4.1.0
Installing ri documentation for activemodel-4.1.0
Parsing documentation for activerecord-4.1.0
Installing ri documentation for activerecord-4.1.0
Parsing documentation for rails-4.1.0
Installing ri documentation for rails-4.1.0






Done installing documentation for rack, concurrent-ruby, sprockets, erubis, builder, thread_safe, tzinfo, i18n, activesupport, actionview, rack-test, actionpack, sprockets-rails, bundler, thor, railties, mime-types, polyglot, treetop, mail, actionmailer, arel, activemodel, activerecord, rails after 569 seconds
25 gems installed
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
zogy@ubuntu:~$ 
