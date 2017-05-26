# Capistrano Config
[![Greenkeeper badge](https://badges.greenkeeper.io/grrr-amsterdam/capistrano-config.svg)](https://greenkeeper.io/)


# Methods
## `.getConfig(string target)`
Attempts to retrieve local Capistrano configuration.
Expects a target name of the environment.
It will look for `[environment name].rb` for a Capistrano configuration in your local path.

Returns a Promise containing a config object.
