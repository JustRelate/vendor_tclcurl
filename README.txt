Download von: http://personal1.iddeo.es/andresgarci/tclcurl/english/download.html
Installation:
    -> ./configure --with-curlprefix=<Project>/External/curl/<OS>/<Version> --prefix=/tmp/tclcurl --exec-prefix=/tmp/tclcurl --disable-threads
    -> make
    -> make install

    lib-Verzeichnis nach External/tclcurl/<OS>/<Version>/kopieren.

2) TclSh
    -> export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/tmp/curl/lib 
    ->% lappend auto_path /tmp/tclcurl/lib/TclCurl0.15.3/
    ->% package require TclCurl
         Version von TclCurl (0.15.3) sollte angezeigt werden
