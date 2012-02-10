![logo](https://github.com/baskerville/hestia/raw/master/logo/hestia_logo.png)


    SYNOPSIS
        hestia <action> [arguments]

    ACTIONS 
        list
            View current downloads.

        queries
            View all queries.

        search TERMS
            Search for TERMS on all networks.

        results [QID ...]
            View the results of the given queries.

        forget QID ...
            Forget the given queries.

        add FID ...
            Download the given files.

        pause FID ...
            Pause the given downloads.

        resume FID ...
            Resume the given downloads.

        cancel FID ...
            Cancel the given downloads.

        preview FID
            Preview a download. 

        priority VALUE FID ...
            Change the priority of given downloads.

        kill
            Kill the mldonkey daemon.

## Requirements

- python 3
- mldonkey
