# OpenTagPostamCollection
Repository with Postman GraphQL collection for OpenTag technical interview
<br>
Task Review:
<br>
1.<i>Retrieve and store all species that have participated in the first movie of
Star Wars “A New Hope".</i>
<br>
<b>Explanation:</b> All the species were retrieved with this request but didn't stored anywere since it wasn't mentioned in the task
<br>
2.<i>Obtain “name”, “birthYear”, “homeWorld”, “eyeColor” for the person, which is “Droid”.</i>
<br>
<b>Explanation:</b> Retrieved "name", "birthYear", "eyeColor" and "homeworld" for Droids based on droid species id, pulus with tests whether those properties are present or not
3.<i>Obtain the totalCount of all people that have participated in the movie and the unique “id”, “name” and “gender” for each of them.</i>
<br>
<b>Explanation:</b> Obtained totalCount value for all the characters participated in episode "A New Hope", but since there weren't any unique id in format which is mentioned in the task like "unique id = 4", in actual response it's more like "cGVvcGxlOjQ=" , so I decided to take a 4th node in the list wichi is Darth Vader and work with his ID
<br>
4.<i>Using the information received by previous request, obtain the “name”,“birthyear”, “homeWorld”, “eyeColor”, starshipName for the person with unique id = 4 </i>
