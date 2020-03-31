# Social Distancing

### Understanding social distancing by programming

In this problem we are providing you with the insight were you can understand the importance of social distancing.

Your task is to create a queue of Customers, each customer having following properties:


1. String name
2. Character gender
3. String mobileNumber
4. String location / city
5. Boolean isInfected
6. Boolean isAwareOfInfection
7. Boolean isAwareOfSocialDistancing

These are the properties of each customer
* name can not be null, can contain full name or first name, or last name.
* gender can not be null, can be M or F or T.
* mobileNumber can not be null, can be number only or with std code or with country code.
* location can not be null, can contain a String representing city-country.
* isInfected can not be null, can contain true or false.
* isAwareOfInfection can not be null, can be true or false.
* isAwareOfSocialDistancing can not be null, can be true or false.

Now, your task is to Implement a Queue of customers by following below simple rules:
1. If customer infected, he / she cannot be part of queue. When you found such customer print Hospitalized.
2. If customer AwareOfInfection, he / she cannot be part of queue. When you found such customer print Quarantine.
3. If a customer is infected and AwareOfInfection follow rule 1.
4. All other customers can be added in queue, with proper social distancing i.e. there will be gap of three null 
node between two customers.
5. If customer is not aware of social distancing, he will be added just next to existing customer.

To check your implementation, create a main class and follow the steps to process the queue. Read all steps from console.
Steps are:
1. First line contain an integer T, denotes total number of test cases.
2. Second line contain an integer N, denotes total number of coustomer coming tu buys things.
3. Next N line contain comma separated values denoting customer information.

During adding process print Hospitalized or Quarantine as per customer information.
Once when you added all the customer the do the following:
1. Print the queue(i.e. print comma separated details of each customer in new line) and delete one customer.
2. Repeat step 1 until queue is empty.

Sample input

1

8

Vaibhva Diwan,M,09753212321,Mathura-India,false,false,true

Ramesh,M,9865744356,Bhopal-India,false,false,false

Mahesh Sharma,M,+919826798267,Delhi-India,true,true,true

Rukmani,F,9856776544,Bangluru-India,false,true,false

Sunil Ram,M,8864311233,Indore-India,false,false,true

Surbhi Singh,F,8811356554,Ranchi-India,false,false,true

Ankit Kumar,M,9093312320,Patna-Bihar,false,false,false

Gurmeet,F,9977258877,Ambala-India,false,false,true



### Your Queue should look like
Its just a symbolic queue not your output.

[Social Distancing Queue](Social%20distancing%20in%20queue.bmp)