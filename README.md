# Slack Utility Tools

# Usage

## Create a Slack App and issue token

First of all, you have to create [slack app](https://api.slack.com/apps) and issue the token.

Every time you run the script you need to set it as an environment variable.

```bash
set SLACK_API_TOKEN="your-app-token"
python invite_to_times.py
```

## Install pipenv

This project is managed with [pipenv](https://github.com/kennethreitz/pipenv) for virtual enviroment.

```bash
pip install pipenv
pipenv --version
```

```bash
pipenv install --dev # Including package for development.
pipenv run python invite_to_times.py
```



# Futures

## Invite to channels named 'times_XXX'

this script invites all users to all 'times_XXX' channel.

```bash
pipenv run python invite_to_times.py
```

### what 'times_XXX' channel ?

[Refer here](http://c16e.com/1511101558/)

