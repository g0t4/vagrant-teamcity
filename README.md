To run TeamCity:
`vagrant ssh` into the box
`cd /opt/TeamCity`
`sudo ./bin/runAll.sh start`

Server will ask a few questions the first time you start it about the data directory and the database type to use with TeamCity.

To stop the server:
`sudo ./bin/runAll.sh stop`
