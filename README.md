# DDEV Development Environment

This repository provides a Qucosa development environment powered by [DDEV](https://ddev.com). For more information check out the [DDEV documentation](https://ddev.readthedocs.io/).

## Start and Configuration

1. `ddev start` to start all containers
2. `ddev composer install` to install TYPO3 and all extensions
4. `ddev import-db -f db.sql.gz` to import a prepared database
5. `ddev launch typo3` to go to the TYPO3 backend login page

## TYPO3 backend credentails

Username: admin
Password: admin
