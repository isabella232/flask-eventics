# `flask-eventics`

This is a [Flask Blueprint](http://flask.pocoo.org/docs/0.10/blueprints/) for generating [iCalendar files](https://www.ietf.org/rfc/rfc2445.txt). 

It is not complete.

## Configuration

`flask-eventics` can optionally use the Flask app configuration or
environment variables for configuration. 

* `CALENDAR_PRODID` is the iCalendar product identifier for generated
  calendars.

## Requirements

* [Flask](http://flask.pocoo.org/)
* [Python icalendar](http://icalendar.readthedocs.org/en/latest/) 
* [Python mock (for the tests)](http://www.voidspace.org.uk/python/mock/)


