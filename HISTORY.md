Release History
===============

master
------

**Enhancements**

* Allow `Slideshow` to be used as a context manager. [#18](https://github.com/vinayak-mehta/present/pull/18) by [Clint Lawrence](https://github.com/clint-lawrence).

    Also, the earlier duct tape fix `os.system('reset')` (to not leave the terminal in an abnormal state after exit) is replaced with a `screen.close()` which is much better because the earlier fix wouldn't work on Windows.

* Move an element to the center when there is only one on a slide. [6a0b045](https://github.com/vinayak-mehta/present/commit/6a0b045d0837dc05729d45427c6fae66a1d197ad) by Vinayak Mehta.

0.3.0 (2020-08-20)
------------------

**Enhancements**

* [#17](https://github.com/vinayak-mehta/present/issues/17) Raise informative error when image file does not exist. [564fa72](https://github.com/vinayak-mehta/present/commit/564fa727ec66eda93684dfaa25b7f6f5a4033972) by Vinayak Mehta.

**Bugfixes**

* [#16](https://github.com/vinayak-mehta/present/issues/16) Add variable size for h1 headings. [446385d](https://github.com/vinayak-mehta/present/commit/446385d75690bac940e3eeb665b9118f10c8aed4) by Vinayak Mehta.

0.2.0 (2020-08-20)
------------------

* First working release!
