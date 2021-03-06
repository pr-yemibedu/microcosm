# Microcosm - Social Network Simulator

Microcosm is a social network simulator tool that allows your clients to see how well the social network you're trying to build scales with millions of users, millions of likes, millions of follows/unfollows.

To run the Simulation Engine, invoke it like this: <code>node bin/microcosm.js user:create</code> or <code>node bin/microcosm.js simulator:follow</code>

<pre>
  Blast Radius: PROJECT MICROCOSM by @jbueza
  Usage: microcosm &lt;command&gt;
  where &lt;command&gt; is one of:
  	 user:create, user:delete
  	 simulator:follow, simulator:unfollow, simulator:random
  	 simulator:like, simulator:vote, simulator:view, simulator:share
  	 simulator:gherkin
</pre>

Note: Please do not use for production use, as I am still taking feedback from several mentors/friends! If you have any feedback
on how the engine will use gherkin lexicon to dictate how the simulation engine behaves, please feel free to reach
out to me at [jbueza@gmail.com](mailto:jbueza@gmail.com).

Cheers and thanks,
Jaime

## Data Bindings

* CSV - Allows your social network to be full of users based on CSV data
* JSON - Allows your social network to be full of users based on JSON data
* Facebook - Allows your social network to be full of users from Facebook (generated users)
  * Opens up simulated Check Ins API
  * Opens up simulated Like API
  * and more!
* LinkedIn
* Twitter

## TODO

* npm package-ify this using ngen
* tests

## License 

(The MIT License)

Copyright (c) 2011 Jaime Bueza

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.