tlc
===

Tail Lines in Color

A simple text colorizer.
Provide a config file name (required) and stream something to stdin.

Examples
--------

Example usage from the commandline:

    tail -f /var/log/httpd/error_log | tlc

    tail -f /var/log/httpd/error_log | tlc ~/.some_tlc_config


Example line to stick in your .vimrc which will map 'gl' in movement mode to tail follow the Apache error log:

    :map gl :!sudo tail -f -n 2500 /var/log/httpd/error_log \| ~/dev/tlc/tlc<CR>

(Adjust to wherever your tlc binary is)


Silly Lines
-----------

This line has the word platypus in it.

