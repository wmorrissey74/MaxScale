#Changelog

These are the changes introduced in MaxScale version 1.0.6

* New modules added
      * Binlog router
      * Firewall filter
      * Multi-Master monitor
      * RabbitMQ logging filter
* Added option to use high precision timestamps in logging
* Readwritesplit router now returns the master server's response
* Minimum required CMake version is now 2.8.12 for package building.
* Session idle timeout added for services
* The logs can now be configured to have millisecond precision