# AWS EC2 SnapshotAlyzer
Demo project to manage AWS EC2 instance snapshots

## About
This project is demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring
shotty uses the configuration file created by AWS cli E.g.

`aws configure --profile shotty`

## Running
`pipenv run python shotty/shotty.py <command> <sub-command> <--project=PROJECT>`

*command* is instances, volumes, or snapshots
*sub-command* is list, start, stop or depends on <command>
*project* is optional
