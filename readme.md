# Media Server

[한국어](./readme.ko.md)

## Features

- Serves static media files.
- Provides video streaming.


## Installation

1. Clone the repository.

2. Modify the .env file (enter the desired port and project name).
    ```
    APPNAME=appname
    PORT=8899
    ```
3. Run the build script:
    ```bash
    ./build.sh
    ```
    or
    ```bash
    sh build.sh
    ```

4. Open your browser and go to `http://localhost:8899/media/`. Enter the file name according to the path.



## Discussion Points
- The default is 1 week, but it is managed by storing it in a cookie for 3 hours for now. <<Period, organization method needs discussion>>
- Log file management (whether to initialize periodically based on capacity or keep accumulating).