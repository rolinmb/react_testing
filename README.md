Made with react.js and google firebase

.csv files for time-series data and option chain data are generated by a separate, locally ran python script

TODO: add ability to upload chain .csv and or time series .csv files to Firebase Cloud Storage

src/dummy_creds.js represents where you would enter your own Google Firebase project credentials; obfuscated here for obvious reasons,
just note that src/firebase.js is referenced in all of the live code instead of src/dummy_creds.js

Rolin Blake (rolinmblake@gmail.com)