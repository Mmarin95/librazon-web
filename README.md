# librazon-web



Just a library web built using NodeJS expressjs. It stores info about authors and its books in a MongoDB database.
A home page shows the most recent added books.
The Author section shows a list of authors where they can be viewed, edited or deleted. The authors can be searched with a search-bar. Author view show also its books.
The books section includes a search/filter form and shows the book's list.
We can add authors and books. As well as the book covers using Filepond library.

### Tricky things

#### Express Modules

- `dotenv`
- `ejs` Template Engine
- `method-override` Able forms to do REST verbs
- `body-parser` Allows JSON communications.
- `mongoose` 

#### - Mongoose 

- Virtual types. Get cover image as base64.
- `.pre()` hook on "remove". Check if author has books.

#### CSS 

- Modularized by pages with variables for a easy change.
- variables.css + sections.css imported to a main.css as well the fonts.
