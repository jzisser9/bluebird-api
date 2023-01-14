# BlueBird API

On or around January 12, 2023, Twitter's APIs went down without any notice, breaking many third-party integrations.
There is suspicion that this was intentional so that all Twitter users would be forced to use the official Twitter app
and web site.

This project attempts to preserve a third-party, open-source API so that users have options besides the official Twitter
app and web site.

# Problems

* Without an official API to pull from, BlueBird API (known from here onward as "the API") will need to scrape Twitter's
  web site and collect data from the HTML. This could cause API requests to take relatively long to complete.
* This data will need to be cached in a database so that future requests will respond more quickly. We need to decide
  what the TTL of cached data will be.
    * We should also consider setting up scheduled jobs to update data in the database constantly.

# Contributing

BlueBird API is an open-source project. Issue and commit submissions are welcome.

TODO: Pull request and issue templates will be forthcoming.

To contribute code, please create a new feature branch off of `main`, develop your solution, and ensure it has proper
testing. Then, open a new pull request pointing at `main` and fill in the template. A project administrator will review
your change.

To open a new issue, please go to the Issues tab and create a new issue, and fill out the template.