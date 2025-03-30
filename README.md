# pricelabs
# Assignment.js - Fetch Listings and Generate CSV
Problem Statement: Write a script that will take an address (and coordinates) and a page size as arguments and use the aforementioned API to fetch data and generate a CSV file containing the following 4 columns.
- Listing ID
- Listing Title
- Page Name
- Amount Per Stay

## Overview
This script fetches property listings based on a given address and coordinates, then generates a CSV file containing relevant details. It retrieves the data using an API and outputs the following columns:

- **Listing ID**
- **Listing Title**
- **Page Name**
- **Amount Per Stay**

## Prerequisites
Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- npm (comes with Node.js)

## Installation & Setup
Follow these steps to set up and run the script:

### 1. Clone the Repository
```sh
git clone <repository_url>
cd <repository_name>
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Script
Execute the following command:
```sh
node assignment.js [address] [latitude] [longitude] [rowsPerPage]
```

### Example:
```sh
node assignment.js Chennai 13.08784000 80.27847000 75
```

## Expected Output
After execution, a CSV file will be generated in the same directory. The file will be named based on the provided address (e.g., `listings_data_{currentTime}.csv`).
