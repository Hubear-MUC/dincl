dincl.h 1.0
-----------

This header file includes the functions

  din()
  
and

  dout()
  
to your program.

This saves bytes of code space compared to a single  #include - directive for every single of the files for  din()  and  dout().

Also the directive  

  #include <stdio.h> 

which is necessary for  din()  and  dout()  to work is included, so you just need to use

  #include "dincl.h"
  
to be able to in- and output double numbers with your program.



Version history
---------------

Version 1.0

Initial version

