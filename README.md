# Firestore Querying and Filtering Data for Web [A Complete Guide]

Understanding how queries work on the Firestore Database is one of the valuable skills to have as a Firebase Developer as Firestore is getting more popular than the Real-time database. 

In this Firestore tutorial, I will be covering how to do a simple CRUD (Create, Read, Update and Delete) operations with Firestore Database.

After that, you are going to learn how to make queries using WHERE (single/multiple), ORDERBY and LIMIT filters.

Then, I will guide you through how to get sub-collections data Collection Group queries which is one of the new features at the time of this post.

Finally, I am going to be teaching you how to split queries when you have a large collection of documents using pagination with Query Cursor function for a better experience and to save money. 

Sounds interesting! 😯... A lot to cover!

Let's get started. 🚀

Feel free to jump into any section below.

- [Add A Document to Firestore](https://softauthor.com/firestore-querying-filtering-data-for-web/#add-document-to-cloud-firestore)
- [Update A Document to Cloud Firestore](https://softauthor.com/firestore-querying-filtering-data-for-web/#update-a-document-firestore)
- [Delete Data from Cloud Firestore](https://softauthor.com/firestore-querying-filtering-data-for-web/#delete-data-from-cloud-firestore)
- [Get Documents Data from Firestore Database](https://softauthor.com/firestore-querying-filtering-data-for-web/#get-documents-from-firestore-database)
- [Get A Single Document Data](https://softauthor.com/firestore-querying-filtering-data-for-web/#get-a-document-from-firestore)
- [Get Data from Sub-collection](https://softauthor.com/firestore-querying-filtering-data-for-web/#get-data-from-firestore-subcollection)
- [Firestore Single/Multiple Where Query Filter](https://softauthor.com/firestore-querying-filtering-data-for-web/#single-multiple-where-firestore-query)
- [OrderBy and Limit Filters](https://softauthor.com/firestore-querying-filtering-data-for-web/#order-limit-firestore-query)
- [Collection Group Queries](https://softauthor.com/firestore-querying-filtering-data-for-web/#collection-group-queries-firestore)
- [Firestore Pagination Queries using Query Custors](https://softauthor.com/firestore-querying-filtering-data-for-web/#pagination-with-query-cursors-firestore)


## Add/Create A Document To Cloud Firestore
There are two ways to create/add a new document to the Cloud Firestore. Which are

- add()
- set()

Let’s take a look at add() method sample code.

```
const db = firebase.firestore()
db.collection("users").add({
    name: "Anbu Selvan",
    email: "anbu.selvan@email.com",
    age: 25
})
```
To run the sample code in your project, you will need to add Firebase to your project

First, get a reference to the Firestore database using firestore() method and store it in db.

Then, obtain a reference to the users collection by invoking collection() method on the db object.

Finally,  run add() method by passing new data as a JavaScript object.

[https://softauthor.com/wp-content/uploads/2019/07/firestore-add-data.png](https://softauthor.com/wp-content/uploads/2019/07/firestore-add-data.png)

[Continue Reading]()
