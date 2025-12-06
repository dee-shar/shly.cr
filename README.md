# shly.cr
Web-API for [shly.link](https://shly.link/) which serves as an url shortening service 

## Example
```cr
require "./shly"

shly = Shly.new
short_url = shly.shorten_url("https://example.com")
puts short_url
```
