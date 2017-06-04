# data-objects

## Overview

`school-data-example.js` populates a _PounchDB_ instance from school data sourced from data.delaware.gov.
It creates some indexes for the the data and then runs queries using these indexes.


## Running example

```
npm install
npm run clean-db-artifacts
npm run init-db
npm run query-example
```

or

```
npm install
rm -rf schools schools-mrview-*
node load-school-data.js
node school-data-example.js
```