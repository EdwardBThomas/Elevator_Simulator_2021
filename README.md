# Elevator_Simulator_2021
Powershell code for a textual simulation of my Elevator Control Narrative.

Let's start with how this will by necessity be different from a real implementation of the Elevator Control Narrative (ECN or CN)...
  1.) The real implementation depends on an external camera on the cabin reading QR codes printed inside the shaft and a cache of the current floor stopped on, or the most-recent floor stopped at, to calculate the rate of change when going to the next floor.
    1.1) For the sake of laughs, this simulation won't have an upper limit of floors. You will be able to enter any floor number and the program will iterate another floor between entries--it will just output something (say, the current Delta F and Anti-Delta F tables) and ask the user to press enter to proceed to the next iterated floor.
      1.1.1) So already, we see the n+1 increment function will play a role in how the 'rules' govern this simulation.
