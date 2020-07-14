# FinTrack Import configurations #

This repository contains all preconfigured CSV import configurations supported by FinTrack. If you want to import a CSV file check this repository for a bank in your country and download the corresponding configuration file.

### Adding a new configuration ###

If your bank is not yet listed in the repository then it would be appreciated if you add the configuration using the following steps:

* Fork the repository
* Clone the fork you made
* Locate the country code of the country your bank is located in, create a new directory if it does not yet exist
* Create a new file with your bankname
* Commit the file and create a pull-request into this repository

The file you created should be under:


```
<country code>/<bank name>.json
```