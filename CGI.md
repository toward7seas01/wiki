
* unescape(string,encoding=@@accept_charset)

URL-decode a string with encoding(optional).

  string = CGI::unescape("%27Stop%21%27+said+Fred")
     # => "'Stop!' said Fred"

