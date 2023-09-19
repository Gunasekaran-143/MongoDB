# MongoDB
Learning MONGODB

# First install Mongodb and Mongoshell
<img width="960" alt="Screenshot 2023-09-19 212828" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/739f669d-9de5-4eed-974f-ed89deed13a9">

# Then create a command and insertone data by using ( insertOne ) command
In mongo db we all do in javascript and json fornmat

<img width="362" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/f4c3f87b-075e-443b-856f-1ff30cc2987b">

# to see what are the details available in DB (FIND)
<img width="573" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/dbe7f45d-8828-4516-859f-b0048ed8fd91">

# we can create different ways: Example: In address we nested street and Hobbies are created in within array

<img width="860" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/a39f2004-cbdf-47c8-b967-3026e76f759a">

# Many(We can create many document we want with the help of i((insertMany)) keyword)
<img width="590" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/75d27a89-762e-435a-ba97-b50f98437b08">

# Display first 2 entries only (db.users.find().limit(2))
<img width="497" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/db039c9d-6501-433f-8b0f-a7909c883357">

# sorting a to z (1) z to a (-1)
<img width="528" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/37bfe81a-989b-4d92-9e31-b4d753001fac">

# skip commmand will skip


# find command what we given we have to search exactly
<img width="540" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/ec3f23e3-1783-4494-9afb-9f569e7c74a5">
if you see in this example first i search small letter gunasekaran but can't find 
but <br>
If I search "Gunasekaran" it will show the match of data <br>
So it is case sensitive

#  more commands: 
mydb> db.users.find( { age: {$gt: 29 }} ) # greater Than
mydb> db.users.find( { age: {$gte: 19 }} ) #greater than equal

mydb> db.users.find( { age: {$lt: 19 }} )#less than

mydb> db.users.find( { age: {$ls: 19 }} ) #less than equal

mydb> db.users.find( { name: { $eq: "Gunasekaran"}}) equal to 
mydb> db.users.find( { name: { $ne: "Gunasekaran"}}) ne: not equalto

mydb> db.users.find( { name: { $nin: ["Gunasekaran","suresh"]}}) NOTin db
mydb> db.users.find( { name: { $in: ["Gunasekaran","suresh"]}}) NOTin db

<img width="960" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/60baf020-3780-4b5d-9f8e-12e25c4172fb">


# if you dont need object give _id:0 
<img width="960" alt="image" src="https://github.com/Gunasekaran-143/MongoDB/assets/134137559/45a21580-0429-4a9d-b5d1-fa1ba3e3e457">


