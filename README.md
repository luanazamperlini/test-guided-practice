# test-guided-practice

Use a text editor to complete the following:

You were hired by a global hotel chain to redesign the functionality of the button panel on their elevators. The goal is to replace the outdated panel in over 1,200 different locations. Before you begin coding, you should make a list of all the ways these panels should be tested to make sure they are working correctly and respond to unexpected input in a way that makes sense. Remember to consider happy and unhappy paths! 

To complete this guided practice, write as many Unit Tests as possible. If time allows, write at least one integration, functional, and acceptance test. Be sure to label each test with its associated type (Unit, Integration, Functional, Acceptance).  

Note: the answers provided below are just some of the many tests that you could have written! 


#UNIT:
# Press the door botton calling the elevator. 
- The button lights up indicating it has recognized your request.
- The closest elevator will be sent to your floor.
- Wait for the elevetor to signalize that it has arrived at your floor by the sound signal.
- Once the door is open, walk in.
# Push the button indicaring the floor you want to go.
## Push the button >||< to close the door "manually"
## Push the button <||> to keep the door open for as long as it is pressed.
## Push the "bell" button in case you have an emmergency and need to contact someone outside.
- The button light lights up, indicating it has recognized your request.
- Wait for the door to close. Or hold the door, so the elevator won't move for as long as you are dolding it open.
- The door closes and the elevator starts moving up or down depending on the floor you walked in.
- When the elevator arrives to your requested floor, the button light turns off, the sound signal signilize that it has stopped on the floor and the door opens.

#INTEGRATION:

- While on operation, the elevator will work acordedly to the order of requestes from inside of it. The buttons to request the elevators will be unavailable until it starts going to the requested direction. If going down, its gonna go all the way down before it goes up.

#FUNCTIONAL:

- Startes on the 2nd garage floor
- Goes up to the Lobby
- Goes up to the 3rd floor
- Goes back to the Lobby
- Goes back to the 2nd garage floor

#ACCEPTANCE:








