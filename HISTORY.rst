History
=======

0.2.0 -- 2014-02-24
-------------------

- Add ability to tell ``MultipartEncoder`` which encoding to use. By default 
  it uses 'utf-8'.

- Fix #10 - allow users to install with pip

- Fix #9 - Fix ``MultipartEncoder#to_string`` so that it properly handles file 
  objects as fields

0.1.2 -- 2014-01-19
-------------------

- At some point during development we broke how we handle normal file objects.  
  Thanks to @konomae this is now fixed.

0.1.1 -- 2014-01-19
-------------------

- Handle ``io.BytesIO``-like objects better

0.1.0 -- 2014-01-18
-------------------

- Add initial implementation of the streaming ``MultipartEncoder``

- Add initial implementation of the ``user_agent`` function

- Add the ``SSLAdapter``
