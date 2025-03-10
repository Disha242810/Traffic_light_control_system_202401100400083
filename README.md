# Traffic_light_control_system_202401100400083
The Traffic Light Control System generates a random integer as time till which the program runs and returns the last state whether RED, YELLOW or GREEN.
The program uses two libraries of python that are time and random, from random we use randint method to generate an integer between a range (here 100 to 696 seconds), and then start the states from RED to GREEN until we reach the randomly generated time.
The approach to solve this problem starts with generating a random number as time in seconds between the range 100 to 696. And then starting the Traffic Light Control from RED to GREEN until we reach the generated time. 
And returning the number of states passed and the last state.
