# django_mysql_retry_init

[![Build Status](https://travis-ci.org/efischer19/django_mysql_retry_init.png?branch=master)](https://travis-ci.org/efischer19/django_mysql_retry_init)
[![Coverage Status](https://coveralls.io/repos/github/efischer19/django_mysql_retry_init/badge.svg?branch=master)](https://coveralls.io/github/efischer19/django_mysql_retry_init?branch=master)

Django backend extension implementing the recommendations at
https://docs.docker.com/compose/startup-order/ for the case of a
django application using MySQL.

This is for startup only, I make no attempt at dealing with lost
connections during operation.

## Django version support
I've targeted (and test against) each django/python version pair that
is listed [on djangoproject.com](https://docs.djangoproject.com/en/1.11/faq/install/#what-python-version-can-i-use-with-django), with the exception of 1.9 which
is [unsupported](https://www.djangoproject.com/download/#supported-versions).

| Django Version | Python Version(s)  |
|----------------|--------------------|
|       1.8      | 2.7, 3.3, 3.4, 3.5 |
|      1.10      | 2.7, 3.4, 3.5      |
|      1.11      | 2.7, 3.4, 3.5, 3.6 |
