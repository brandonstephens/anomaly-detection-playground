# Anomaly Detection Playground

A place to play with the concepts found in [this lovely article](https://hakibenita.com/sql-anomaly-detection) by Haki Benita.

This comes with a big bunch of [data from Google](https://observablehq.com/@observablehq/google-merchandise-sales-data).

## 💾 Installation

### Docker Setup

1. Install docker
2. `docker-compose up -d`

### Database Setup

1. Add the database TablePlus using:
   <mysql://root:password@127.0.0.1?statusColor=F8F8F8&enviroment=local&name=Anomaly%20Detection%20Playground&tLSMode=0&usePrivateKey=false&safeModeLevel=0&advancedSafeModeLevel=0&driverVersion=0>
2. Launch the `Anomaly Detection Playground` DB from TablePlus
3. Select `Open` from the File menu
4. Select the `setup.sql` from this repo
5. From the SQL editor (which should have loaded the `setup.sql` file) select `Run All` which may be burried uner the `Run Current` button.
6. Be patient there is lots of data import.

### Once setup

1. `docker-compose up -d`
2. Launch TablePlus
3. Select `anomaly_detection` database
