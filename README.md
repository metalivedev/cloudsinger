What Is This?
-------------

This code shows how use [Twilio](http://twilio.com/) with
[Sinatra](http://sinatrarb.com) on [DotCloud](http://www.dotcloud.com/).

Sinatra provides a clean, classy DSL for doing simple applications and
Twilio provides an __AWESOME__ REST API for doing cloud telephony. This
demo just scratches the surface of what you can do with Twilio (and
dotCloud really).

To run this code on dotCloud, you need to [get a dotCloud
account](https://www.dotcloud.com/accounts/register/).

Then clone this repository:

    $ git clone git://github.com/caleywoods/cloudsinger.git

And push it to DotCloud:

    $ cd cloudsinger
    $ dotcloud create -f live cloudsinger
    $ dotcloud push

Happy hacking! Remember: each time you modify something, you need to
git add + git commit your changes before doing `dotcloud push`.

How Does It Work?
-----------------
If you want to see how this sample app was built, we invite you to:

* see the big picture with GitHub's awesome [compare view](https://github.com/caleywoods/cloudsinger/compare/begin...end) --
  click on each individual commit to see detailed explanations for each step
* if you prefer text mode (or offline inspection), fallback on
  `git log --patch --reverse`
* dive into [dotCloud documentation](http://docs.dotcloud.com/), especially
  the one for the [Ruby service](http://docs.dotcloud.com/services/ruby/)
  which is used by this app.
