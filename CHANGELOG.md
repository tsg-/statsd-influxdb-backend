StatsD InfluxDB backend - CHANGELOG
-----------------------------------

## v0.9.3 (2017-06-28)
Updated documentation on how to use our statsd-influxdb-backend fork in the project

## v0.9.2 (2017-06-28)
Added possibility to disable appending proxy suffix to metric name

## v0.9.1 (2017-06-28)
Merged changes from https://github.com/nevins-b/statsd-influxdb-backend

## v0.9.0 (2017-06-28)
Merged changes from https://github.com/gillesdemey/statsd-influxdb-backend

## v0.8.0 (2017-03-15)
* Fork from [https://github.com/guydou/statsd-influxdb-backend](https://github.com/guydou/statsd-influxdb-backend) into
  ccycloud namespace
* merge statsd tag functionality from [https://github.com/gillesdemey/statsd-influxdb-backend](https://github.com/gillesdemey/statsd-influxdb-backend) 
  into this version 
  
## v0.7.0 (2016-10-01)

* Modified `defaultRetentionPolicy` to work with new databases created in influxDb v1.0

## v0.6.0 (2015-06-23)

* Initial InfluxDB 0.9 API support (#14, #17)
* Make username and password config options optional. (#15)

## v0.5.0 (2015-04-02)

* Unbreak conditional. (#13)
* Updated regex for statsd metrics. (#12)
* Expose internal backend metrics. (#9)

## v0.4.1 (2015-02-23)

* Use prefixStats setting instead of hardcoding prefix. (#6)

## v0.4.0 (2015-02-22)

* Add configuration option to enable sending internal statsd metrics. (#6)
* Add SET support. (#7)
* Fix problem with histograms breaking data flushes. (#8)
* Add SSL support. (#3)
* Improve configuration example in README.

## v0.3.0 (2014-08-24)

* Allow gauges with a value of 0 to be sent. (#2)
* Update `time_precision` to use `ms`. (#1)

## v0.2.0 (2013-11-19)

* Add flush strategy and enable it by default.
* Add configuration options for flush and proxy strategy.

## v0.1.0 (2013-11-15)

* Initial release.
