# Team Builder

## Description

The purpose of this project is to help hackers find teammates who are interested in the same kinda project as they are. To help making temas for HackRU easier.
## Inspiration

The mind of Sam Azouzi

Also the awkward team-building events that we've run at hackathons.

## Installation Guide

You need python, pip, and virtualenv. Please use google to get these on your system.
Here are the shell commands that'll complete the installation. Note that you also need SQLite.
```bash
git clone https://github.com/HackRU/teamRU.git
cd teamRU
virtualenv venv # or your system-specific version (it'll look similar)
source venv/bin/activate
pip install -r requirements.txt
```

To set up the DB, just ask somebody (most likely). We intend to use AWS's RDS and the `attributes.txt` is the schema
you must use to set it up.

You'll have to configure config.example.py (make a copy without the `.example` and put in the DB details).

Much of this is a bit experimental, so we know we're using AWS RDS with MYSQL, but not quite how.

## Example Uses

All solo Hackers looking for a partner or team will use this to help make it easier for them to find teammates with common or just cool ideas.

## Style Guide

:scream:


## TO-DO List
-Make sure everything thats already coded works, and to fix any bugs(Most coding is done but needs to be debugged and polished)

 - Threadhub
 - Dashboard
 - Chat
 - Login
 - Pretty much all HTML

## Links to Further docs

:scream:

## And whatever you want :tada:
Looking for people with knowledge in Python, Flask, and SQL
