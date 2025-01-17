# OrmBenchmark
[![License](http://img.shields.io/:license-MIT-blue.svg)](https://raw.githubusercontent.com/giacomelli/JobSharp/master/LICENSE)

The goal of the ORM Benchmarking project is to determine how long it takes to execute select statement(s) against a MS SQL Server database and map the returned data to POCO/Dynamic objects in different ORMs.

Performance Tests
-----------------

The performance tests are broken in the following lists:

- Performance test of executing one sql command frequently (500 times):
	- Performance of execute one select statement and map a returned row to a POCO object over 500 iterations
	- Performance of execute one select statement and map a returned row to a dynamic object over 500 iterations

- Performance test of mapping database records to POCO/Dynamic objects (5000 row):
	- Performance of mapping 5000 rows returned by one select to POCO objects in one iteration
	- Performance of mapping 5000 rows returned by one select to Dynamic objects in one iteration


How to run the benchmarks
-------------------------

Just download the project and run it or add your favorite ORM as a plugin to the project.
