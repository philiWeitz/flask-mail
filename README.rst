Changes
=======

Changes in flask_mail.py
- changed msg = MIMEMultipart() to msg = MIMEMultipart('related')
- content-type related ensures that email clients (e.g. Thunderbird) show inline images correctly


Flask-Mail
==========

.. image:: https://secure.travis-ci.org/mattupstate/flask-mail.png?branch=master

Flask-Mail is a Flask extension providing simple email sending capabilities.

Documentation: http://packages.python.org/Flask-Mail
