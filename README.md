[![Metabase Logo](http://www.metabase.com/images/logo.svg)](http://www.metabase.com/)

[Metabase](http://www.metabase.com/) is the easy, open source way for everyone in your company to ask questions and learn from data.

# Using the log4j2 configuration

To use the log4j2 configuration, you need to add `-Dlog4j.configurationFile=file:/app/log4j2.xml` to the JAVA_OPTS env variable .

To get a clean parsing, you also need those variables to be set:

- `MB_EMOJI_IN_LOGS`=`false`: Disables emoji in logs
- `NO_COLOR`=`true`: Disables log coloration (https://no-color.org/)

# Running Metabase on Heroku

[Heroku](https://www.heroku.com/home) is a great place to evaluate Metabase and take it for a quick spin with just a click of a button and a couple minutes of waiting time. If you decide to keep your Metabase running long term we recommend some upgrades as noted in the documentation linked to below to avoid limitations of the Heroku free tier.

*tl;dr Click this button to deploy Metabase to Heroku for free.*

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

For more details, check out the [Heroku-specific deploy documentation](http://www.metabase.com/docs/latest/operations-guide/running-metabase-on-heroku.html) for help with:
* Upgrading beyond Heroku's free plan
* Deploying Metabase version updates to Heroku
* Troubleshooting
