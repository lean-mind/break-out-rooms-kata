# Break out rooms kata

When we run workshops via Zoom using break out rooms for several rounds, sometimes we want the people to rotate so that every round they get to practice with different colleagues. When there are 20+ people in total and more than 3 rounds, it's really hard for a human organizer to group people in rooms without repetition. 

As a code kata, write a function that takes the list of attendees, the size of the rooms (number of people per room) and the round number. The function will organize the rooms minimizing the amount of repetition per round. The result of the function is a list of lists containing rooms with participants. The function will be deterministic, given the same round and the same participants and room size, the result will be the same. This will serve as a history. 


