Compile angular app
--------------------------

1. **ng serve** command builds and serves the application from memory for faster development experience. 

2. **ng serve** command does not write the build files to the disk, so we cannot use it for deploying our application on a different server like test server or production server.

3. we use a **ng build** command to deploy application on a development server or test server or production server.

4. When we execute **ng build** command it creates a folder with name "dist" and copies all the build files into that folder.

5. By default the **ng build** command does a development build, not a production build. The development build is not optimised for production use. The development build is typically used for testing. With a development build it is easier to debug as the development build contains source map files.

As you can see in the "dist" folder we have 
1. The favicon
2. Glyphicon files
3. Our host page index.html
4. Bundle files and their corresponding source map files

Please note : Both the following commands are equivalent and does the same thing, i.e they produce a development build
**ng build** or **ng build --dev**

If you want to produce a Production build, use below command.
**ng build --prod**

If you want to deploy the application to a server, copy the contents of the "dist" folder to a folder on the server.
