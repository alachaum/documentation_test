Maestrano Documentation
=======================

Hello World
-----------

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```haml
%table{ style: "width:100%" }
  %tr
    %td{ style: "width:50%" }
      %p Hello
    %td{ style: "width:50%" }
      .highlight
        =@readme_processed.html_safe
```

Adrien
