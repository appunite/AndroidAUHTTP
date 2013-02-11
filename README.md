# AUHTTP
AUHTTP is library designed to simplify using of HttpClient and other network tools

# Run an example

run this command:

    git clone <repository-url> AndroidAUHTTP
    
in eclipse:
 * File -> New -> Android Project from Existing Code
 * select AndroidAUHTTP directory
 * Finish
 * build and run ExampleAUHTTP

in ant:

   	cd ExampleAUHTTP
   	ant debug
   	ant installd

# Embeding in your project

run this command:

   git submodule add <repository-url> AndroidAUHTTP

in eclipse:
 * File -> New -> Android Project from Existing Code
 * select AndroidAUHTTP directory
 * Finish
 * Your project -> properties -> Android
 * Library -> Add..
 * select AUHTTP and OK

in ant:

 * XXX should be sequent number or 1 if first
 * add to your project project.properties file something like: "android.library.reference.XXX=../AndroidAUHTTP/AUHTTP"
 * run those commands:
 
		ant debug
		ant installd
		
# License

    Copyright [2013] [Jacek Marchwicki <jacek.marchwicki@gmail.com>]
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    	http://www.apache.org/licenses/LICENSE-2.0
        
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
