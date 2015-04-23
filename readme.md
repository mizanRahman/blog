My Jekyll Blog
==============

Setup Instructions
-------------------
1. clone the repository
2. install jekyll
		gem install jekyll
3. install rouge to replacing pygment syntex highlighter
		gem install rouge
4. jekyll serve

In case of windows
------------------
In windows there may raise some issues.

- Issue: certificate verify failed
	* update ruby gem
	* help:     https://gist.github.com/luislavena/f064211759ee0f806c88     

- Issue: Native build tool required:
	* install devkit
	* help": http://flatshaded.com/2013/05/installing-jekyll-on-windows/	
- problem with pygments syntex highlighter:
    * use rouge as syntex highlighter. 
    	gem install rouge
    * add rouge to _config.tml. add this line to _config.yml:              
        highlighter: rouge



