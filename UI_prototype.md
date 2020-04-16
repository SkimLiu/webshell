# Graphical User Interface Prototype  

Authors: Michele Filippini, Giovanni Brignone, Andrea Zappavigna, Dong Liu

Date: 16/04/2020

Version: v3

Change history

| Version | Changes                                        |
| ------- | ---------------------------------------------- |
| v3      | Added some description and [credits](#Credits) |
|         | Changed the layout of some pages               |
| v2      | Added some new function pages                  |



## Contents



### GUI Prototype

According to functional and non functional requirements and the user's usage habits and processes, we have designed the following GUI. These images take into our consideration about how to design an automated and efficient system.

##### GUI 1 Sign-Up page, UC9 - FR8 Sign up

<img src="/Users/ledon/Desktop/final/Sign-Up Page.png" alt="Sign-Up Page" style="zoom:33%;" />

This is the user registration page , including five elements: Name, Surname, Email, Username and Password. Unregistered user UR creates a new account and becomes a Registered user through this page. If the email or the username used by another account, the registration process will stop and show a warning of conflicting elements.

##### GUI 2 Log-in page, UC8-FR7 Sign in

<img src="/Users/ledon/Desktop/final/Log-In Page.png" alt="Log-In Page" style="zoom:33%;" />

After completing the registration, Registered user RU can sign in with his email address or username. If RU inserts correct email address or username and password at the same time, it will jump to menu page; If incorrect, it will fail the login authentication and issue warning: Sorry, that email address or username or password isn't valid.

##### GUI 3, Menu

<img src="/Users/ledon/Downloads/ezgas-groupBranch/docs/UI_v2/Menu.png" alt="Menu" style="zoom:33%;" />

Menu page contains three function buttons and one search box. Home button helps the user return to the home page from any page. Settings button can modifty user profiles, language and system configuration, etc. If the current user is a registered user RU, they can click logout button to log out. The search box can be used to search system functions.

##### GUI 4,5 Maps search, Map search 2, UC7 - FR9-10 Search gas station

The application uses the API of maps system in order to retrieve information about the localization of users and gas stations.

<img src="/Users/ledon/Desktop/final/Maps Search.png" alt="Maps Search" style="zoom:33%;" />

Search Gas Station page is an open function for all users, it display the search results filtered by some filters on the map, such as fuel type, services, destination and payment method, etc. For example, if the user wants to search which stations can provide Benzina, he can click fuel type and choose Benzina. The results will show on the map system. In order to be able to show more clearly, the user's selection will be bolded and ticked. 

<img src="/Users/ledon/Desktop/final/Maps Search 2.png" alt="Maps Search 2" style="zoom:33%;" />

If the user wants to filter by price, he can drag the dot to select a different price range. if the research yields no results, issue warning.

##### GUI 6 Gas Station New, UC1 - FR1,FR15 Add new gas station

<img src="/Users/ledon/Desktop/final/Gas Station New.png" alt="Gas Station New" style="zoom:33%;" />

Add new gas station is a function for registered user RU and RU is logged in. RU inserts the position through the map system, the name and the gas company which the gas station belongs and sends a request to add the gas station in the application. All fields are mandatory. If the station in the given inserted position already exists in the application, issue warning and the request is not sent.

##### GUI 7 Gas Station Detail, UC3 - FR3 Delete gas station

<img src="/Users/ledon/Desktop/final/Gas Station Detail.png" alt="Gas Station Detail" style="zoom:33%;" />

Gas station detail page provides some basic information for users like gas station name, fuel and prices, services and supporting payment methods, but only registered user RU can edit those information if they find something incorrect. Furthermore, if the user finds the gas station doesn't exist, he can send a request to delete this station, and this station will be removed from this application when system receives requests higher than a certain threshold. At the end of page, the position shows in text, click to display on the Map system. Opening time also shows at the end.

##### GUI 8,9 Gas Station Edit, Gas Station Edit 2, UC2 - FR2 Update gas station

<img src="/Users/ledon/Desktop/final/Gas Station Edit.png" alt="Gas Station Edit" style="zoom:33%;" />

RU selects the gas station and one of the possible update to do : update the name, update opening hours, update payment method or update services offered. RU also can report wrong information here.

<img src="/Users/ledon/Desktop/final/Gas Station Edit 2.png" alt="Gas Station Edit 2" style="zoom:33%;" />

##### GUI 10 Fuel New, Fuel New Add, UC4 - FR Add fuel type and price

<img src="/Users/ledon/Desktop/final/Fuel New Add.png" alt="Fuel New Add" style="zoom:33%;" />

Gas station G is stored in the application, Registered user RU is logged in, it is possible to select the types of fuel among those not yet present in G. Then RU inserts the related price and add new fuel to system.

##### GUI 11,12 Fuel Edit, Fuel Edit 2, UC5 - FR5 Update fuel price, UC6 - FR6 Delete fuel type and price

<img src="/Users/ledon/Desktop/final/Fuel Edit.png" alt="Fuel Edit" style="zoom:33%;" />

If registered user RU find some update information about fuel types and prices, they can log in and select it to update and change it. After submitting, the new price has been successfully updated and RU username and time of the update are stored in the system.

<img src="/Users/ledon/Desktop/final/Fuel Edit 2.png" alt="Fuel Edit 2" style="zoom:33%;" />

If RU finds that a certain fuel type no longer exists, he can remove it. As the same, the username of RU and time of the update are stored in the system.

### Credits

ICONS from the Noun Project

Gas station by Kantor Tegalsari

Home, Tools and Power by i cons

Plus by Rohith M S

Tag By Icons8

Search by Rizky Mapat Waluya

Bin by Alice Design from the Noun Project

PHOTO from Unsplash

Gas station by Justin Chrn