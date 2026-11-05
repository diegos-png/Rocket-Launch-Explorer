GITHUB REPO: https://github.com/diegos-png/Rocket-Launch-Explorer.git

API USED: https://lldev.thespacedevs.com/2.3.0

API DOCUMENTATION: https://ll.thespacedevs.com/docs/#/launches

This is a practice webdev assignment to get familiar with XMLHttpRequest and Axios


At first, I used XMLHttpRequest object to call the API. I would create the object, send the request using .send and .open. Finally I used an anonoymous function on .onreadystatechange to parse the data and then I make a callback with that parsed data.

the function populateDropdown gets passed into getUpcomingLaunches as a callback to start the progrom off and fill the dropdown.

^^ The code is still in the functions, but commented out.


Then, I used Axios to get the same results.

Axios does the same things but with less set up. a .get sends, recieves, and parses the data for me. The .then handles a resolved Axios promise and the .catch handles a rejected Axios promise