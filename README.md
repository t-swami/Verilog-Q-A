# Verilog-Q-A
Here I would like to post the question and answers related to the Veriog designing which i found in the LinkedIn.

Question and Answers:

Q1:  Given an input stream of 0s and 1s, detect the first occurrence of 1. Once the first 1 is detected, output should be 1 continuously for the rest of the stream.




Projects:

P1: Traffic Light Controller
-- using the FSM concept,assuming a junction and written this program based on the state diagram. 
P2: Traffic Light  Controller using the sonsors (x,y) or Switches to control
-- This Code is written by assuming the 2 way road with 2 traffic lights opposite to each other, and they can be contol by the switches or the sensors (x,y);
    1. Let assume the x connected to one side and y is connceted to other side.
    2. Normally it works like a normal traffic lights system but when they sensors or swithes triggers the logic 1 then they can switch to respected operation like allowing to 
      to go on one side only or when they both triggers then allows both direction to go. 

P3: Vending machine using FSM
    --using the FSM concept, assuming the types like tea and coffee.
    --The user has to select the type he wants and then he has to insert the coin. 
    Initially the system is in idle state and when the user select the type then it moves forward and then the user has to insert the coin, if it is
    correct then it can dispense the selected item,else it shows the invalid coin or invalid state.
    The dispense is on untill the timer runs and then it can goes to idle state.

    
P4: Electronic Voting Machine
    --Using behaviourial Modeling, assuming 3 candidates to participate
    --When the respected switch means c1,c2,c3 of the candidate is trigger at the clock pulse then it can increment the count of the respected              candidate vote by 1. 
    When the end voting is trigger, taking of votes is ended and it has to compare the votes of the candidates and then show the winner. In the comparision it compare whether if any 2 or more candidate has the similar no:of votes, if yes then it can rises the signal of the respected signal else it can compare the votes of each candidate then announce the winner.







......................................................................................................................................................

If you are facing any doubt feel free to ask via this details:
Name: Talla Narayana Swami
Phn : 9014389160
Email: swami.8talla@gmail.com
linkedin: https://www.linkedin.com/in/swamitalla/




