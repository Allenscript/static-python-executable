# static-python-executable
build your script to executable 



1.  build python library

   ```py
   ./configure --prefix=/usr/local/pythonversion --enable-shared
   make
   make install altinstall
   ```

2. build your executable binary

   ```
   python static-build.py test_file.py /path/to/static/libpythonX.X.a
   ```

   

