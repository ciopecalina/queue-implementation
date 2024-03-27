# queue-implementation
Implemented a queue as a LinkedList or ArrayDeque using Queue.
1. LinkedList class can be used as a stack that stores the elements in a doubly linked list.<br />
2. ArrayDeque class uses an array to store elements.<br />

# Application - Queue at the counter 🚶‍♂️🚶‍♀️🚶‍♂️🚶‍♀️🚶‍♂️
I simulated a queue of people waiting to be served at a counter.<br />
A person will be represented by a string (the person's name), so the collection entities will be of type String. <br />
<br />
|            Action                  |         Method        |           Details                                 |
| :--------------------------------- | :-------------------- | :------------------------------------------------ |
| find the next person in line            | String whoIsNext()      | Will query the collection to find the next person.                       |
| add a new person                   | void addPerson(String)   | Adding made on the last position.     |
| serving a person                 | String servePerson()    | The method leads (by default) to removing the person from the queue.      |
| check if document queue is empty   | 	boolean areMorePersons()     | Returns true if there is at least one person left in the queue and false otherwise.
