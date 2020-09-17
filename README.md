# **Frq controll** 
## The wills
    - checks for unexpected updates in user variables
    - alows to chain variables as alternating inputs and detect if those are stuck
    - checks if "fagile" inputs are abused
    - prompts server with warnings about potential brute-force attacks
    - allows to set routines activated by activities set as "red flags"
## The maybies
    - is split in user part and server which would not sacrifice performance,  
      unless someone is breaking rules (well they deserved it i guess)
    - returns warning to the user side about rules he is about to break
    - handles server side "emergency protocols"
        - allows to set personalized "emergency protocols"
        - has built in key protocols 
## The don'ties 
    - no permament loop mumbo jumbo
    - no dumb functions for every case which means modular checks based on one parent function
