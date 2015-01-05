Facebook Graph API OAuth Example
================================

A simple Sinatra-based example of the new Facebook Graph API.

Setup
-----

All you need to do is to configure your OAuth identity:

    @client_id = "YOUR-CLIENT-ID-HERE"
    @client_secret = "YOUR-CLIENT-SECRET-HERE"

That's it? Yep!

Now you can give it a spin:

    ruby -rubygems facebook-oauth-example.rb
    open http://localhost:4567/
