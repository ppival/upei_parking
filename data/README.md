# Data Files

**Parking Permit Information 2018-01-16 08_47.xlsx** is the Excel file that I received from the University of PEI in response to my Access to Information request. It contains data on student parking permits issues from May 2017 to December 2017.

**upei-parking-permits-201705-to-201712.csv** is a cleaned up version of the Excel file as a CSV:


1.     I removed 7 records that were missing a model year for the vehicle.
1.     I converted the model years to four-digit dates.
1.     I trimmed spaces from the ends of the vehicle information rows (it looks like their were exported originally as a fixed-width file, with spaces for padding).
1.     I removed the anonymous identifier column, as I didn’t required it for my purposes.
1.     I split the “vehicle information” field into 3 fields: year, make and model (this is what I’d originally specified in my request, but they came as one field). In doing so I found there were several records that were missing the model, but I left them in place with only the year and make.
