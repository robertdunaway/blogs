---

title: jQuery 2.x or jQuery 1.x ??
tags: 
- jQuery
- Continuous Improvement
- IE8
- Greenfield

---

#jQuery 2.x or jQuery 1.x ??


If you employ "Continuous Improvement" in an effort to battle technical debt you'll need to consider the direction of jQuery in your decision to upgrade.  Even your incremental upgrade strategy may have consequences you weren't prepared for.


##Upgrading to 2.0

If you simply upgrade to 2.0 from 1.x and run your tests everything will work just fine.  That is until you receive calls from angry about features no longer working.

###Why?!

Because you are a developer and work with Greenfield browsers.  jQuery 2.x drops support for IE 8 and lower.   jQuery 1.x will still be around for these older browsers.  jQuery staff recommend you use jQuery 1.9 if you think there is a chance some of your user base is still using IE 8.
http://jquery.com/upgrade-guide/1.9/

###Either will work
The jQuery API is consistent between 1.9 and 2.0 so when the time comes you are convinced you no longer need to support IE 8 you can swap in the 2.0 release and benefit from the performance increase without changing code.

#In theory…

So, of course we test our code when we update libraries… right?  Right.  In the case of jQuery 2.0 don't just test but make a conscious decision on which path to take.  1.9 or 2.0.  IE 8 or not IE 8.Enjoy...


http://jquery.com/download/