What
====

Demo app to demonstrate an AngularJS `$http.put` redirection bug. If a put request has a redirection as a result, AngularJS gets stuck making repeated network requests.

![](https://raw.github.com/rktjmp/angularjs-http-put-loop/master/screenshot.png)

How
===

Visit http://angularjs-http-put-bug.herokuapp.com/

or

    clone the repo
    cd <repo-dir>
    bundle
    rails server
    visit http://localhost:3000/
    Add a post so we have something to "put" to.
    Click "test put" and look at your network inspector.

