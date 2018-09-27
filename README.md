# Logs Analysis

> Supriya Kijakkar

## About

Informative summary from logs is a real task that comes up very often in software engineering.
This project will answer questions about the site's user activity.

## To Run

### You will need:
- Python3
- Vagrant
- VirtualBox

### Setup
1. Install Vagrant And VirtualBox
2. Clone this repository

### To Run

`vagrant up` - To launch Vagrant 
`vagrant ssh` - To login 
`psql -d news -f newsdata.sql` - To load the data & run command to connect to DB and run sql queries.

The tables:
- Authors table
- Articles table
- Log table

`python3 newsdata.py` - To execute the program. (from command line)
