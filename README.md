BlogPostsWeb Introduction
===========

BlogPosts is an Open Source web application for blogging. It use google app engine and 
Slim3 framework for database and server side. BlogPosts website use also Java, Javascript, jQuery and bootstrap for 
some of the features. The website can be used together with BlogPostsAndroidApp (which you can find it also here). 
This is an Android app for receiving notifications when a new articles is posted.

There are two groups of people using the BlogPosts website - users and bloggers.
BlogPosts allows the users to read the new articles and the bloggers to add new articles.
There are two main pages - the 'Home' page, containing all the articles with small description and article detail 
page for seeing the whole article with bigger picture.There is functionality to subscribe for one or more categories 
and also there is a category search and page navigation bar.

There is a hidden login menu for bloggers in the footer, the button is on the "c" icon. The bloggers should be added 
statically in the database, but once they exist, they can login and make a new post. There is also functionality the 
new articles to appears on first position in the Main page.

Setup
===========

In Eclipse, you should install App Engine if you do not have it. You should add this plugin to eclipse.
Help > Install New Software and then click on "Add" button and paste this - http://dl.google.com/eclipse/plugin/4.3 on location.

You also need to install Slim3 so that you can run the project successful. The same way you should add the plugin for
Slim3 - http://slim3.googlecode.com/svn/updates/

After you install the plugins, just clone the project from Git or import as an Slim3 project. 
Project > Clean to generate the binaries you need, like R.java, etc.
Now if you have errors, Right click on the project > Properties > expand Java Compiler > Annotation Processing > Factory Path >
click on Enable project specific settings and then from 'Add JARs' add the slim3-gen-1.0.15.jar file.
If there are some other errors and the compiler cannot find the json library, you should add it to the build path.

Developed By
===========

Maya Gardeva and Ivan Collantes
    
    
License
===========

Copyright 2014 iMobilize Ltd.

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.
