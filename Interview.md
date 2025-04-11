April-11-2025
1. End to end JS apps
2. What is NodeJS?
3. JavaScript Engine is a program that executes JavaScript Code
4. JS Code -> JS Library + C/C++ features + Dependencies(v8,libuv,zlib,crypto,e.t.c)
5. iffe -> Immediately Invoked Function Expression
    E.g. : (function(){
                const name = "Madhu";
                console.log(name);
            })();
6. Module Wrapper 
    E.g. : (function(exports,require,module,__filename,__dirname){
                const name = "Madhu";
                console.log(name);
            })();