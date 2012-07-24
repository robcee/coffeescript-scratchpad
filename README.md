coffeescript-scratchpad
=======================

CoffeeScript context for Scratchpad. Patch for Firefox.

To play with this, you'll need to [apply this patch](https://developer.mozilla.org/en/Mercurial_Queues) to a source tree and [build firefox](https://developer.mozilla.org/En/Simple_Firefox_build).

https://github.com/robcee/coffeescript-scratchpad/blob/master/coffeescript#L85

This line is Bad. This is not how we want to do this, but we should be able to take our selected text in the scratchpad and send it to CoffeeScript.run().

warning: HAX