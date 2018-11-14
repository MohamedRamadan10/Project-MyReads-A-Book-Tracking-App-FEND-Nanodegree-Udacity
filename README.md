# MyReads: A Book Lending App

> Mohamed Ramadan 

## About

This is the first project for the Udacity React Nanodegree. This project emphasizes the use of React with a given API server. The starter template contains the CSS and HTML for the project but omits the React code. I was able to build the React components to populate the main page and search page with books. THe main page has three shelves that users are able to move the books between shelves. The search page allows users to search for new books to add to their shelves. After selecting books to add to shelves, when you navigate back to the home page the you can instantly see the selections made on the search page. This project uses React's setState to build the functionality to move books from one shelf to another.

## Getting Started

1. run `git clone https://github.com/MohamedRamadan10/Project-MyReads-A-Book-Tracking-App-FEND-Nanodegree-Udacity.git` to clone this repository
2. then run `npm install`
3. `npm start` to start the app then navigate to http://localhost:3000/ on your local machine

## Specifications

In this application, the main page displays a list of "shelves" (i.e. categories), each of which contains a number of books. The three shelves are:

-   Currently Reading
-   Want to Read
-   Read

The homepage of the MyReads App shows the title "MyReads" and then three shelves, which are named "Currently Reading," "Want to Read," and "Read." There are books on each shelf. Each book has a green circle in the bottom right-hand corner. The app has a green plus sign icon in the bottom right-hand corner.

![](https://d17h27t6h515a5.cloudfront.net/topher/2017/May/590c0f12_react-project1-a/react-project1-a.png)

The static page (and your completed app) should look something like this.

Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there. Note that the default value for the control should always be the current shelf the book is in.

The green circle in the right-hand cover of the first book is clicked. You see a menu that has the following options: "Move To," "Currently Reading," "Want to Read," Read," and "None." The "Move to" option is greyed out. There is a checkmark next to the "Currently Reading" option.


![](https://d17h27t6h515a5.cloudfront.net/topher/2017/May/590c0f26_react-project1-b/react-project1-b.png)

The main page also has a link to  `/search`, a search page that allows you to find books to add to your library.

The search page has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library. To keep the interface consistent, you may consider re-using some of the code you used to display the books on the main page.

![](https://d17h27t6h515a5.cloudfront.net/topher/2017/December/5a3c22b9_screen-shot-2017-12-21-at-1.06.59-pm/screen-shot-2017-12-21-at-1.06.59-pm.png)

When a book is on a bookshelf, it should have the same state on both the main application page and the search page.

![](https://d17h27t6h515a5.cloudfront.net/topher/2017/July/595d48a9_correct-use-of-state/correct-use-of-state.gif)

The search page also has a link to  `/`  (the root URL), which leads back to the main page.

When you navigate back to the main page from the search page, you should instantly see all of the selections you made on the search page in your library.
