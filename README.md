# PyOpenSSL
Solution for "ImportError: cannot import name PyOpenSSLSocket" error in Calculate Linux systems

A simple workaround solution for "ImportError: cannot import name PyOpenSSLSocket" error in Calculate Linux systems. The error appears when you try to start cl-console-gui or cl-console-gui-update commands.

The error is caused by unsuccesful import of PROTOCOL_SSLv3 and RAND_egd functions in pyopenssl_wrapper.py module.

Simply replace pyopenssl_wrapper.py file in /usr/lib64/python2.7/site-packages/sudsds/transport/ directory with modified file from repository.
