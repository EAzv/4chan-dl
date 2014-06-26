Dependencies
========
* [Python 2.7+](https://www.python.org/)
* [Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/)

Usage
========

    Usage: 4chan-dl <options>

    Options:
        -s --section=section    4Chan section
        -c --code=code          4chan thread code
        -f --folder=folder      Download folder, if not exist I create it
        -v --verbose            Verbose output
        -h --help               Display this help

    Example usage:
        -Download image from /g/ in current folder:
            4chan-dl -s /g/ -c 41908404
        -Download image from g (or /g/ is the same) in folder and verbosity on:
            4chan-dl -s g -c 41908404 -f /home/fdisotto/4chan -v
