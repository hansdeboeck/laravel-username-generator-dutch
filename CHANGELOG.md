# Changelog

All notable changes to `laravel-username-generator` will be documented in this file.

## 1.2.0 - 2026-08-23

- removed 'schimmelvis' from the noun list
- raised the dev dependencies to pest 4.7, pest-plugin-laravel 4.1, collision 8.9.5,
  testbench 10.11 or 11.0 and laravel-ray 1.43.9
- the test matrix now covers PHP 8.4 and 8.5 against Laravel 12 and 13
- fixed `composer test`, which aborted because the phpunit configuration requested
  coverage reports without a coverage driver being available

## 1.1.0 - 2026-04-28

- added support for Laravel 13

## 1.0.0 - 2022-01-19

- initial release
