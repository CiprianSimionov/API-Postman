
# Postman

Below are some test samples that I've practiced with.

*URL - http://qachallenge.ro/api/*

Create user by first name and last name.

Method: POST

Parameters:
key: first_name & value: Ciprian

key: last_name & value: Simionov

![create](https://github.com/CiprianSimionov/API-Postman/assets/26772192/eae630dd-bab3-4da2-b29b-b3a0a33c7c1f)

-----------------------------------------------------------------------

*URL - https://openweathermap.org/forecast5*

Weather forecast for 5 days with data every 3 hours.

Method: GET

Required Parameters:

Lat & lon set to Cluj-Napoca

Appid: Unique API key identifier

Units - metric(for temperature in Celsius), set by default in Kelvin

![read](https://github.com/CiprianSimionov/API-Postman/assets/26772192/7c88550e-11ec-447f-a27a-5ffa044ea023)

-----------------------------------------------------------------------

*URL - https://simple-books-api.glitch.me*

Method: POST

Submit a new order using following parameters:

key: bookID & value: 4

key: customerName & value: default_user

key: quantity & value: 3

![create_order](https://github.com/CiprianSimionov/API-Postman/assets/26772192/19310d5f-6932-4739-871c-94860ac9c74e)

-----------------------------------------------------------------------

*URL - https://simple-books-api.glitch.me*

Method: PATCH

Update an existing order for following properties:

key: customer_name & value: random_user

![update_order](https://github.com/CiprianSimionov/API-Postman/assets/26772192/f91350e9-7645-4687-934d-3912db2929cb)

-----------------------------------------------------------------------

*URL - https://newsapi.org/*

Method: GET

Searching for news articles with following parameters:

required key: apiKey & value: fa3b507495c648eb9c82b061fbef11d2

key: q & value: quasars

key: sortBy & value: popularity

key: from & value: 2023-12-20

![read_articles](https://github.com/CiprianSimionov/API-Postman/assets/26772192/085c52c5-5600-4617-81e7-60f53a9907ca)

-----------------------------------------------------------------------

*URL - http://qachallenge.ro/api/*

Method: DELETE

Delete existing user by id

key: action & value: delete

key: id & value: 868

![delete](https://github.com/CiprianSimionov/API-Postman/assets/26772192/638fdfba-1fc0-4e94-a172-458145497e64)

-----------------------------------------------------------------------









