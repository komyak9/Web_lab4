# Spring + Vue application that detects points in a given area on the coordinate boundary.

The back-end should be based on Spring.
The front-end should be built on Vue.js.
The interaction between the back-end and front-end levels must be organized through the REST API.

#### The start page should contain the following elements:

1. "Header" containing the student's full name, group number and option number.
2. Form for entering login and password. Information about users registered in the system should be stored in a separate database table (the password should be stored as a hash sum). Access of unauthorized users to the main page of the application should be prohibited.

#### The main page of the application should contain the following elements:

1. A set of input fields for specifying the coordinates of the point and the radius of the area in accordance with the assignment option. If the input field allows input of deliberately incorrect data (such as letters in point coordinates or a negative radius), then the application must validate them.
2. A dynamically updated picture depicting an area on the coordinate plane in accordance with the number of the variant and points, the coordinates of which were specified by the user. Clicking on the image should initiate a script that determines the coordinates of a new point and sends them to the server to check if it falls into the area. The color of the dots should depend on the fact of hitting / missing the area. Changing the radius should also initiate a redraw of the image.
3. A table listing the results of previous checks.
4. A button by which an authenticated user can close their session and return to the application start page.

#### Additional application requirements:

1. All verification results must be stored in a database managed by the PostgreSQL DB.
2. You need to use JPA to access the database.

