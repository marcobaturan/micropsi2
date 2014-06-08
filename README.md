about
-----
a Python implementation of the cognitive architecture MicroPsi.

For more information visit [micropsi.com](http://www.micropsi.com).


run
-----
* To just run the micropsi toolkit, copy `config.ini.template` to `config.ini` and adjust to your preferences
* run `./run.sh`
* view in browser at [http://localhost:6543/](http://localhost:6543/)


run with minecraft connectivity
-----
* To run micropsi with minecraft conectivity, you need to call `make` after checkout, and then follow the steps described above
(Minecraft connectivtiy has an additional dependency on pycrypto)
* Also see [micropsi_core/world/minecraft/README.md](/micropsi_core/world/minecraft/README.md) for setup instructions.


attribution
-----
Python MicroPsi uses 

* [spock](https://github.com/nickelpro/spock)
* [bottle](https://github.com/defnull/bottle).