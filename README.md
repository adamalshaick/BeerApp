# Frontend developer coding test
Functional requirements \
Based on following API: http://ontariobeerapi.ca/ please write a beer application. It should consist of:

1. Three column layout, where each column is a list of beers (Beer endpoint) by Brewer (example Molson, Kompania Piwowarska S.A. etc).
2. Initially lists are empty, and there’s a drop-down on top of each one with all possible brewers.
3. After selecting brewer, list is being populated with 15 beers sorted by name. If there’s more than 15 beers of given brewer, there’s “Load more” button in the bottom, which loads another 15 and so on (until all beers are loaded).
4. The selection should be persisted in given , i.e. after refreshing site, application should remember which brewers were used in which columns.
5. Each beer entry consist of Name, Type,  Price per litre and image thumbnail.
6. Image thumbnail should be in a form of circle (radius) with 40px diameter. After clicking on it, full size picture should be visible on overlay centred to the window.
7. There should be settings modal upon clicking on “Options” button somewhere. Options:
1. possibility to change layout theme from light to dark,
2. specifying number of elements loaded in one go (from 15 to 30 for example),
3. sorting by given field, selected from drop-down: name, price, type; after change it should sort already loaded beers.
8. All Options should be cached in the browser, for future reuse.
 
Non-functional requirements
1. Provide archived git repository.
2. Vue.js is preferred.
3. Must be easy to setup and run.
4. Code should be easy to maintain, extend and modify (OOP, SOLID, Clean Code).
5. Providing tests plays in your favour.
6. All comments, descriptions and code must be in English.
Good luck! :-)
