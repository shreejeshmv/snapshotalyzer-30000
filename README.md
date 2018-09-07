# snapshotalyzer-30000
Demo project to manage EC2 instance snapshots

## About

This project is a demo and uses boto3 to manage AWS EC2 instance snapshots

## Configuring

shotty uses configuration file created by the AWS cli.
e.g.
'aws configure --profile shotty'

## Running

`pipenv run python shotty\shotty.py type command --project=<Project_Value>`
*type is instances volumes snapshots
*command is list for instances, volume and snapshots, and start or stop for instances
*project is optional
