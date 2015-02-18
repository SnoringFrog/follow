```
  _|_|            _|  _|
  _|        _|_|    _|  _|    _|_|    _|      _|      _|
_|_|_|_|  _|    _|  _|  _|  _|    _|  _|      _|      _|
  _|      _|    _|  _|  _|  _|    _|    _|  _|  _|  _|
  _|        _|_|    _|  _|    _|_|        _|      _|
```
---

# follow

##About
`follow` is a shell utility used to "follow" the previous command into a directory. It comes in handy if you (like me) find yourself too lazy to type the full `cd` command you need to accomplish the same effect after a `cp/mv/mkdir` command (or anything else with a destination, really). 

You can use `follow` on the same line as a command, or at the next prompt. Currently, only one follow can be used per line (I'm working on changing that though).

##Installation
Clone this repository, copy `follow` wherever you'd like, source it, and use it:
	
	$ git clone https://github.com/SnoringFrog/follow.git
	$ cp follow/follow /path/to/follow
	$ source /path/to/follow

I recommend adding `source "/path/to/follow"` to your `.bashrc` instead of manually sourcing `follow` every time.

##Usage
Here's a quick demonstration: 

![follow examples](/examples.png)

Another good use is when you `cd` into `/some/long/directory/but-accidentaly-add-a-file-at-the-end` so you just get a "not a directory" error. Use `follow` afterwards to get to that directory. Even if you catch your error before hitting enter, `follow` might be faster than backspacing.  

---

Copyright :copyright: 2014 [Ethan "SnoringFrog" Piekarski](https://github.com/snoringfrog)

Modification/redistribution permitted under terms of the [Artistic License](http://www.perlfoundation.org/artistic_license_2_0) (Short version: do what you want as long as you say where the original came from).
