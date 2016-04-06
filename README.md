# ltry
the little try-catch that could

## what is this?
this is a very small try-catch implementation (12 lines, 231 chars including tabs)

## usage
``` lua
local try = require 'ltry'

try(
  function()
    something_that_might_break()
  end
):catch(
  function(msg)
    print(msg)
  end
)
```
