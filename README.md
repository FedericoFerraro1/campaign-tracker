# campaign-tracker

Tool to track and analyze student election campaign contacts.

## Why this exists

Student organizations run election campaigns on shared spreadsheets: volunteers
email hundreds of students, then manually record who said yes, no or maybe, and
how many preferences each person gave. Counting is slow, error-prone, and
coordinators keep asking volunteers for updated numbers to build their charts.

This project aims to replace the spreadsheet with a small tool that stores contact
outcomes in a structured way and produces the statistics coordinators need.

## Status

Work in progress: planning stage. Nothing runs yet.

## Roadmap

- [ ] Specification: data fields and the three charts coordinators ask for most
- [ ] Python script that reads a CSV file and computes counts and trends
- [ ] Automated tests for the counting logic
- [ ] Web interface for volunteers to enter outcomes
- [ ] Database, user roles and deployment on a Linux server

## Planned stack

Python, Git/GitHub, Linux (Ubuntu), pytest, SQL.

## Privacy

This repository contains no real personal data. All sample data is synthetic,
and data files are excluded through `.gitignore`.

## Author

Federico Ferraro, Computer Engineering student at the University of Palermo.
