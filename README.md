# dev
# Batch Runs
## Overview
This package facilitates batch runs for your simulations.

## Installation
To install the package, follow these steps:

1. Open a terminal.
2. Change directory to `batch_runs_package`:
   ```cmd
   cd batch_runs_package
   ```
3. Run the `build_and_install.bat` script:
   ```cmd
   build_and_install.bat
   ```
## Usage
   ```cmd
   run_batches
   run_batches [--xlsx XLSX_FILE_PATH] [--csv CSV_FILE_PATH] [--SERVER_URL SERVER_URL]
   ```
If no arguments are provided, `run_batches` will run with the default XLSX and CSV files and the default API Gateway `SERVER_URL = https://nbmbz5znsb.execute-api.us-west-2.amazonaws.com/dev/simulation/resi/v1/simulationjob`.

### Arguments
- `--xlsx XLSX_FILE_PATH`: Path to the XLSX file containing batch job parameters.
- `--csv CSV_FILE_PATH`: Path to the CSV file containing batch job parameters.
- `--SERVER_URL SERVER_URL`: Optional. The URL of the server to get batch results.

Refer to the `run_batches` command above for more details on usage.

