vagrant
------------------------------------
###### vagrantについて

・vagrantを使うことによってVMの設定をファイルで管理できるようになる

・複数のマシン郡を一度に管理できる

・ロールバックができる

##### vagrantの起動まで

1.vagrant公式からdebファイルをダウンロード、パッケージの展開

2.vagrant init precise32 http://files.vagrantup.com/precise32.box
 ここで自分はinitまでしか書いていなくて手こずった

3.vargrant upで起動

4.vagrant ssh で仮想マシンにSSH接続する

※vagrant destroy でvagrantを削除できる
-------------------------------------
