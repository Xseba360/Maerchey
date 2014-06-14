Maerchey
==============================================
Archey remake... in bash! Designed for usage in Maemo 5.

Screenshot
----------
Coming soon!

Installing
----------
* **As root:**
 * Put the **maerchey** file in **/usr/bin**
 * Open **/etc/profile** in your favourite editor
  * At the end add a line:
  ```
  maerchey
  ```
  * My file looks like this:
  ```
  # /etc/profile: system-wide .profile file for the Bourne shell (sh(1))
  # and Bourne compatible shells (bash(1), ksh(1), ash(1), ...).
  
  export PATH="/usr/bin:/bin"
  
  umask 022
  source /etc/osso-af-init/af-defines.sh
  maerchey

  ```
* Open your terminal and check if everything works!
As simple as that.

Software requirements
---------------------

* lsb_release (>= 3.2)
* busybox-power (>= 1.22)

Author
-------

**Xseba360 (Sebastian Gładki)**


Copyright
---------

The MIT License (MIT)

Copyright (c) 2014 Sebastian Gładki

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
