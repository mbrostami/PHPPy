
# PHPPy

Run your php project as stand alone executable file. 
 
Do these steps :    
1. Download portable python 2.7 and place all files inside "Python" folder.
		[PortablePython2.7.5.1](http://portablepython.com/wiki/PortablePython2.7.5.1/)    
2. Download UniformServer and place all files in "UniServer" folder.
		[uniformserver](http://www.uniformserver.com/)    
3. Download cefpython and extract all files to "UniServer/cefpython" folder.
		[cefpython1-27.0-win32-portable](http://cefpython.googlecode.com/files/cefpython1-27.0-win32-portable.zip)    
4. Move default-httpd.conf to UniServer/usr/local/apache2/conf folder and change setting if you need.    
5. Move php-sample.ini to UniServer/usr/local/php folder and change setting if you need.    
6. Move my-sample.ini to UniServer/usr/local/mysql folder and change setting if you need.    
7. Move and replace localhost.pyw and phpmyadmin.pyw to /UniServer/cefpython folder.    
8. Copy your PHP project files inside "UniServer/www" folder.      
Now if you run phpmyadmin.pyw with PythonW-Portable.exe you can access to phpmyadmin .     
At least duble click on Start.bat.      
If you need to change default URL you should modify "localhost.pyw" and "phpmyadmin.pyw".     