# daria-extract

Temporary CI helper: downloads a DariaOS OTA on a GitHub runner (14 GB disk),
extracts the `vendor` partition, and uploads only a handful of camera/flash HAL
libraries + `/vendor/etc` camera configs as a small artifact.

Used to diff against a Volla Quintus (algiz) ROM to find what enables the torch
strength slider. Delete this repo after extraction.
