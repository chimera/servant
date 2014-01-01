# Servant

This is the repository for the Arduino sketch we're using to control our electronic door latch system. 

**It's very stupid**

If it receives a string of `"1"` via the serial connection at a baud of *19200*, it does a *digital write* to *pin 7* which opens our electronic door latch. 

Ideally we could would not have to use an Arduino to do something so simple, but it works and we're a bit lazy.

The arduino is called by our [door](https://github.com/chimera/door) Golang library.


## License

MIT


## Credits

Written by [Dana Woodman](http://danawoodman.com).
