**This is a fork of [Parsedown Extra](https://github.com/erusev/parsedown-extra) that adds the option to use ':' for target attribute**

__Usage in Markdown:__

`[some link text](link URI){:_blank}`

The above example creates this HTML code:

`<a href='link URI' target='_blank'>some link text</a>`

I kinda got used to the target attribute when I used to use Jekkyll and Kramdown parser to run my blog. 

Working on my own PHP-based Markdown blogging platform, there was no option to integrate Kramdown (it requires Ruby environment) so I decided to add that feature to the awesome Parsedown Extra class.
