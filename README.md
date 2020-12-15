# CS-465-Full-Stack-Development-I
## Architecture
#### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
One of the types of frontend development that was used for this full stack project was Express. Express was used to set up a web server to listen to incoming requests and return relevant responses. In addition, it defined a directory structure where one folder was set up to serve static files in a nonblocking way.

#### Why did the backend use a NoSQL MongoDB database?
I believe that the backend utilized the NoSQL MongoDB database because of its document-style approach to storing data. While SQL databases use columns to define the name and data type, and rows to represent a different entry, MongoDB does not use this schema. Instead of a column defining what should be in the row, each row is a document, and this document both defines and holds the data itself. This less-structured approach means that a collection of documents could have a wide variety of data inside. This allows you to create indexes on more than just the unique identifier field, and query indexed fields much faster. You can also create some fairly complex queries against a MongoDB database. The biggest advantage of using MongoDB is its data modeling feature which defines what data can be in a document and what data must be in a document. When storing user information, you may want to be able to save the first name, last name, email address, and phone number. But you need only the first name and email address, and the email address must be unique. This information is defined in a schema, which is used as the basis for the data model.

## Functionality
#### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON is a JavaScript way of holding data. Rather than a MongoDB document holding a data set that corresponds to a set of columns, a document holds name/value pairs, which makes a document useful in its own right because it both describes and defines the data.

#### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.


## Testing
#### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.


## Reflection
#### How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
