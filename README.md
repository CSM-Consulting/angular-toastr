Fork of **angular-toastr** v2.1.1 for bug fixes. See the [original](https://github.com/Foxandxss/angular-toastr) for documentation.

  - **2.1.2** \
Modified ```toastr.js``` to move ```delete openToasts[message]``` to before toast removal animation.\
This was creating an issue where if a toast was removed and then the same toast created,\
the new toast would not be added if ```preventOpenDuplicates``` was ```true```.
