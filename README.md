# Telegram-server
This is my configuration files for telegram-dev.
* [Инструкция по использованию Git](http://cluster.krc.karelia.ru/doc/rukovodstvo_GIT.pdf)

VIM
----
#### Для работы vim его необходимо собрать из исходников:
    $ sudo apt install python3-dev lua5.1 lua5.1-dev git
    $ git clone https://github.com/vim/vim.git
    $ ./configure --enable-python3interp=yes --with-python3-config-dir=/usr/lib/python3.5/config-3.5m-x86_64-linux-gnu -enable-luainterp=yes
    $ make
    $ sudo make install
