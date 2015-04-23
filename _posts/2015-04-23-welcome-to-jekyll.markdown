---
layout: post
title:  "Welcome to Jekyll!"
date:   2015-04-23 23:39:37
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}


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
- In windows there may raise some issues.

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

            
Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
