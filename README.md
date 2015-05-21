Blackfire PHP SDK 
=================

Only use the [Blackfire](https://blackfire.io/) PHP SDK when:

 * You already have XHProf installed and cannot install the Blackfire PHP
   extension (think PHP 5.2 or HHVM);

 * You want a fallback in case the Blackfire PHP extension is not installed on
   some machines (manual instrumentation will be converted to noops).

Read more about using this PHP SDK in this [Blackfire blog
post](http://blog.blackfire.io/blackfire-for-xhprof-users.html).

**WARNING**: This code should only be used when installing the Blackfire PHP
extension is not possible.

This repository also includes a small proxy script that allows one to inspect
the traffic between profiled servers and blackfire's servers.
Please read the instructions in `./bin/blackfire-io-proxy.php` to do so.