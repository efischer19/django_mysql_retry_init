# django_mysql_retry_init

[![Build Status](https://travis-ci.org/efischer19/django_mysql_retry_init.png?branch=master)](https://travis-ci.org/efischer19/django_mysql_retry_init)
[![Coverage Status](https://coveralls.io/repos/github/efischer19/django_mysql_retry_init/badge.svg?branch=dev%2Factive)](https://coveralls.io/github/efischer19/django_mysql_retry_init?branch=dev%2Factive)

Django backend extension implementing the recommendations at
https://docs.docker.com/compose/startup-order/ for the case of a
django application using MySQL.

This is for startup only, I make no attempt at dealing with lost
connections during operation.
