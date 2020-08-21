# First-PWA

Use Case: AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

This app uses the Node, Express, and MongoDB to create a service worker which provides offline functionality. When a user inputs data in an offline environment, the data is stored in IndexedDB until the user restores online functionality. When online functionality is restore, the data is updated in the database. 