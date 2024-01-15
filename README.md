
# Postman

Below are some test samples that I've practiced with.

*URL - http://qachallenge.ro/api/*

Create user by first name and last name.

Method: POST

Parameters:
key: first_name & value: Ciprian

key: last_name & value: Simionov

![create](https://github.com/CiprianSimionov/API-Postman/assets/26772192/4fe04370-855b-4308-98a6-bf0d08413bdc)

-----------------------------------------------------------------------

*URL - https://openweathermap.org/forecast5*

Weather forecast for 5 days with data every 3 hours.

Method: GET

Required Parameters:

Lat & lon set to Cluj-Napoca

Appid: Unique API key identifier

Units - metric(for temperature in Celsius), set by default in Kelvin

![read](https://github.com/CiprianSimionov/API-Postman/assets/26772192/3cf878de-d1f6-49d4-9bba-e48743173f21)

-----------------------------------------------------------------------

*URL - https://simple-books-api.glitch.me*

Method: POST

Submit a new order using following parameters:

key: bookID & value: 4

key: customerName & value: default_user

key: quantity & value: 3

![create_order](https://github.com/CiprianSimionov/API-Postman/assets/26772192/f312c13d-6a5d-4067-9010-3dbf53ae93a7)

-----------------------------------------------------------------------

*URL - https://simple-books-api.glitch.me*

Method: PATCH

Update an existing order for following properties:

key: customer_name & value: random_user

![update_order](https://github.com/CiprianSimionov/API-Postman/assets/26772192/f9300922-174d-46a8-aff6-86f9cfa94dbb)

-----------------------------------------------------------------------

*URL - https://newsapi.org/*

Method: GET

Searching for news articles with following parameters:

required key: apiKey & value: fa3b507495c648eb9c82b061fbef11d2

key: q & value: quasars

key: sortBy & value: popularity

key: from & value: 2023-12-20

![read_articles](https://github.com/CiprianSimionov/API-Postman/assets/26772192/da430f1c-a978-4b31-8ad3-4c0a344f1e89)

-----------------------------------------------------------------------

*URL - http://qachallenge.ro/api/*

Method: DELETE

Delete existing user by id

key: action & value: delete

key: id & value: 868

![delete](https://github.com/CiprianSimionov/API-Postman/assets/26772192/52c53c28-1b63-4ac2-8f29-9be202bff2b6)











