# Api_AssigmentGet authentication token using URI: https://postman-echo.com/basic-auth
Question:![q1.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq1.png)


How did you get the response?
Get information about all users using URI: https://reqres.in/api/users
Question:![q2.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq2.png)


How many lists can you see in the response body?
>ans:- 1
Get information about the user with id 3 using URI: https://reqres.in/api/users/3
Question:![q3.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq3.png)

How many lists can you see in the response body?
>ans:-none
> 
What are the available property(Key) names in the response body?
>ans:-primary key is 2,under the primary data key there have 5 key,and under the support key there 2key. 

Delete the User with id 9 using URI https://reqres.in/api/users/9
Question:
![q4.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq4.png)

What is the response?
>ans:-1
How many users are now on the users list? https://reqres.in/api/users
> 
Can you see the deleted user record?
>ans:-yes i can see the deleted record.
Get information of the user with id 40 using URI: https://reqres.in/api/users/40
Question:![q6.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq6.png)
> 

How many lists can you see in the response body?
>ans:-there no list.
What are the available property(Key) names in the response body?
> ans:-no property key in the response body.
Create a new user in a system using URI: https://reqres.in/api/users Verb: POST Request Body:

        { 
          "name": "yourname",  
          "job": "dreamjob"
        }
img.png

![q7.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq7.png)

Question:

What is the response code?
>ans:-201
What are the available property(Key) names in the response body?
> ans:-4
What is the value of response Header Etag?
> ans:-W/"55-JT+H1L46nv8/FVlo33cY6rhonZ0"
> 
Sign in to the system using URI: https://reqres.in/api/login and {"email": "peter@klaven"}
Question:
What is the response code?
>ans:-400
Sign in to the system using URI: https://reqres.in/api/login and
{
"email": "eve.holt@reqres.in",
"password": "cityslicka"
}

Question:
What is the value of response Header Etag?
>ans;-W/"25-Ik70kof1lbc973ShN5FoVPxYn7A"
What is the response?
> ans:-400
Get information about all planets using URI: https://swapi.dev/api/planets. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
> Ans:-every object have 2 list name results and flim
>
Get information about the third planet using URI: https://swapi.dev/api/planets/3/
Question:
How many properties you can see in response body?
>Ans:-14 properties in response body.
Get information about all the starships using URI: https://swapi.dev/api/starships. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
> 
> Ans:-initially one list called "result"under "result"there 37 records and there are "flims"and "people"
> each record.
> 
Get information about the ninth starship using URI: https://swapi.dev/api/starships/9/
Question:
How many lists can you see in the response body?
>Ans:-2 list in reponse body.
> 
Get information about all films using URI: https://swapi.dev/api/films. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
>Ans:initially one list call "result" under the result there 6 record and there are characters ,"planets"
>"starships","vehicles",species" in each record the response body.
Get information about the third planet using URI: https://swapi.dev/api/species
Question:
How many lists can you see in the response body?
> Ans:-initially one list call "result" under the result there 10 record and there are"flims"and "people
> each record in response body.
Get all booking ids using URI: https://restful-booker.herokuapp.com/booking
Question:
How many lists can you see in the response body?
> ANs:-1 list in response body.
Get details about booking id 23 using URI: https://restful-booker.herokuapp.com/booking/23
Question:
What is the response?
> Ans:-200.
Get details about booking id 3 using URI: https://restful-booker.herokuapp.com/booking/3
Question:
What is the response?
> Ans:-200.
Get information about all planets using URI: https://swapi.dev/api/planets
Question:
What is the response?
> Ans:-200
How many lists can you see in the response body?
> Ans:-initially one list call "result" under the result there 9 record and there are"flims"and "residents"
> each record in response body.
Get information about all species using URI: https://swapi.dev/api/species. Carefully observe the response body and make a list of all attributes and write their data types.
Question:
How many lists can you see in the response body?
> Ans:initially one list call "result" under the result there 37 record and there are"flims"and "people
> each record in response body.
What is the response?
> 200
Write JSON path for following JSON file:
{
"studio": {
"movie": [
{
"category": "history",
"director": "John",
"title": "History",
"rating": 6.60
},
{
"category": "comedy",
"director": "Paul",
"title": "Laugh",
"rating": 4.00
},
{
"category": "fiction",
"director": "Jack",
"title": "Wake",
"isbn": "87877676879",
"rating": 8.01
},
{
"category": "drama",
"director": "Edward",
"title": "Wuthering Heights",
"isbn": "8754543578",
"rating": 4.50
}
],
"music": {
"song": "pale",
"rate": 5.4
}
},
"ranking": 20
}
a. To retrieve all direct properties of the studio object
>ans:-{
"studio": {
"movie": [
{
"category": "history",
"director": "John",
"title": "History",
"rating": 6.60
},
{
"category": "comedy",
"director": "Paul",
"title": "Laugh",
"rating": 4.00
},
{
"category": "fiction",
"director": "Jack",
"title": "Wake",
"isbn": "87877676879",
"rating": 8.01
},
{
"category": "drama",
"director": "Edward",
"title": "Wuthering Heights",
"isbn": "8754543578",
"rating": 4.50
}
],
"music": {
"song": "pale",
"rate": 5.4
}
},
"ranking": 20
}
b. To find out the music’s song
> ans:-.studio.music.song
> 
c. To find the rating of all items in the studio
>ans:-first rating-studio.movie[0].rating,second rating-studio.movie[1].rating.third rating-studio.movie[2].rating
d. To retrieve information on all movies
> ans:-studio.music.rate
e. To find out the titles of all movies
> >ans:-History,Laugh,Wake,Wuthering Heights.
> 
f. To retrieve the titles of all movies by Jack
>ans;-Wake
g. To retrieve the category of the last movie
> ans:-Drama.
i. To retrieve all movies that have the isbn property
> ans:-Wake,Wuthering Heights
Get information about all employess using URI: http://dummy.restapiexample.com/api/v1/employees
Question:
How many lists can you see in the response body?
> >ans:-1
What is the response?
> ans:-200
What are the available property(Key) names in the response body?
> ans:-"id":
"employee_name":
"employee_salary":
"employee_age":
"profile_image":
Make a list of all attributes and write the data types.
> ans:-"employee_name":
"employee_salary":
"employee_age":
"profile_image":
Get a single employee data using URI: http://dummy.restapiexample.com/api/v1/employee/3
Question:
How many data you can see in response body?
> ans:-5 data
What is the response status?
> ans:-200
> 23.Create a new employee in a system by using URI: http://dummy.restapiexample.com/api/v1/create Verb: POST Request Body:
{
"name":"your name",
"salary":"123",
"age":"23"
}
>Ans:-![q23.png](..%2F..%2F..%2FVideos%2FCaptures%2Fq23.png)
Question:

What is the response?
>Ans:-404
can you see "id" property in the response? if Yes, note the "id" value.
> 
> 
Delete an employee record whose employee id in 2 by using URI http://dummy.restapiexample.com/api/v1/delete/2
Question:
What is the response?
> ans:-404
How many employees are now in the employees list? http://dummy.restapiexample.com/api/v1/employees
Can you see the deleted employee record?
> Ans:-employees was not deleted.
>
Register a user by using
URI: https://reqres.in/api/register Verb: POST Request Body:
{
"email": "john.jack@example.com",
"password": "@izaanSchool"
}

Question:

What is the response?
>Ans:-400
What are the available property(Key) names in the response body?
>Ans:-none


Get an user Using URL https://reqres.in/api/unknown/2
Question:

What is the response?
>Ans:-200
A simple health check endpoint to confirm whether the API is up and running using https://restful-booker.herokuapp.com/ping
Question:

What is the response?
>Ans:-201

Get information using Delayed Response using URI: https://reqres.in/api/users?delay=3
Question:

What is the response?
>Ans:-200
How many seconds delay to respond?
>Ans:-time:3.42 s

Get information about vehicles using URL https://swapi.dev/api/vehicles/schema/
Question:

What type of response it is?
>Ans:-jeson type
What is response status code?
> Ans:-404
Get information about starships using URL https://swapi.dev/api/starships/schema/
Question:

What type of response it is?
>ans:-Jason type
Write down the response status code.
>ans:-404
What are the available property(Key) names in the response body?
> Ans:-Detail