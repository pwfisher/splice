splice
======

SOA FE Node

This experimental framework is far from complete. It is a nice idea, though.

Example usage:

    var splice = require('splice'),
    
        spliceServer = new (splice.Server)({
            pages_dir: __dirname + '/pages',
            static_dir: __dirname + '/public',
            servlets_dir: __dirname + '/servlets',
            static_postscript: 'inc/postscript.html'
        });
    
    spliceServer.listen(8082);
