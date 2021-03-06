![logo](https://github.com/baskerville/hestia/raw/master/logo/hestia_logo.png)


    SYNOPSIS
        hestia <action> [arguments]

    ACTIONS 
        list
            View current downloads.

        servers
            View connected servers.

        queries
            View all queries.

        search [-media <Video|Audio|Doc|Pro>] TERMS
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

        rename FID NAME
            Set FID's filename to NAME.

        info FID
            Retrieve informations regarding FID (requires `mediainfo`).

        names FID
            Display all the known names for FID.

        magic FID
            Display the file magic informations for FID.

        path FID
            Return the path of the file holding FID's content.

        priority VALUE FID ...
            Change the priority of given downloads.

        kill
            Kill the mldonkey daemon.

## Requirements

- python 3
- mldonkey
