### Overview
This directory contains 2 different examples. 
1. Single Page example that consists of 1 HTML file
2. An 11ty website that builds an MD file and serves HTML files.

### Running the example
#### Single Page Example
To run the single page example, just open the HTML file. You may also want to serve it via web server of your choice.

#### 11ty Website
To run the 11ty example, run the following command to install 11ty

```
npm install -g @11ty/eleventy
```

Then, go to the `example/11ty-website` directory and run

```
eleventy
```

to build MD file into html

Afterwards, run the command 

```
eleventy --serve
```

To serve the build file. Since the MD file name is `test.md`, the resulting file is available in `localhost:8080/test`. 

If you made any changes to the `milik.css` file, you need to copy that file to `_site/test/css` directory.