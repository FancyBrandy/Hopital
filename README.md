# Hopital
The whole world is going through a hard time due to pandemic,
and it is important to help patient and provide them with care.

Thus the following simulation:
The printing is done with a protected object.
The 1 min in the text should be 0.1 second when programming.

Patient is a task type which receives the name as discriminant.
A patient chooses one of the available hospitals randomly, and then arrives
after 10 mins, if it is open, enters and prints (his name and hopital number),
if not, after 5 mins tries to enter again, if not, then he goes home, and print that
he cannot enter the hospitals.
20 dynamic patients should be created in an array

The hospital is also a task type.
A hospital takes a random float time to open, after that it allows a patient
to enter each minute.
3 dynamic hospitals should be created in an array, opening at a 2 mins interval.
after 10 mins opening they will close and declare how many patient each one served.

