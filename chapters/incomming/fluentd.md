## Fluentd


|          |         |
| -------- | ------- |
| title    | Fluentd |
| status   | 95      |
| section  | TBD     |
| keywords | TBD     |




Fluentd is a data collector used by many organizations such as Amazon,
Microsoft, and Google[@hid-sp18-526-www-fluentd]. It is open source and
available on GitHub. Fluentd creates a layer of abstraction between the
source of the data and backend, known as the *Unified Logging Layer*.
This centralized system of data collection ensures security and
reliability. Logs contain important information, but due to modern data
sizes, they are no longer for just human use. The purpose of the logging
layer is to allow more machine reading of logs as opposed to human
reading.

In the logging layer, data is converted to json, then sent to the
backend. Fluentd has a plugin system for many different programs, such
as Python and Node.js. There are also custom versions of Fluentd in
production. Google, for example, uses their own version of fluentd as
their logging layer in conjuction with Google BigQuery. The Fluentd
project also includes *Fluent Bit* which is a data forwarding system.
