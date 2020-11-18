# freepbx-stats

Generate infographics about PABX usage from Freepbx CDR Events

## Usage

* Export CSV events

  1. Open FreePBX -> Reports -> CDR Reports
  2. Choose date range -> Check "CSV File"
  3. Click "Search" and the file will start downloading

* Start Notebook server

```sh
git clone https://github.com/flaviostutz/freepbx-stats.git
docker-compose up -d
```

* Open http://localhost:8080/

* Copy the CSV file to "input" dir inside notebook and Run

