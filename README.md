# Fitness Center

A Self-Check In Kiosk for Fitness Center Members

## Description

This is a program simulating a self-check in kiosk for fitness center members to manage membership features including becoming a new member, upgrading membership, checking club, checking in to a fitness center, paying membership fees, displaying membership information, and canceling membership.

### Dependencies

* From the datetime library import the date module.

### Executing program

* Main.py
  our main file to execute the code. It also holds our main function to prompt for user input.
* members_clubs.py
  holds our classes for the different object types involved in our program
* class Member
  parent class to hold member details (member_id and member name)
* class Single_club_member
  a child class of member which assigns a member to a particular club and holds a club instance variable
* class Multi_club_member
  a child class of member which allows a member to use any club and hold membership points as an instance variable
* class Club
  holds information about a particular club including it's name and address. It also holds a class variable of a list of members for the entire 
  program

  

## Authors

Ilackkeya Bhavananthi bsilackkeya21@gmail.com

Riley Sample rcs622.rcs@gmail.com

Brian Levesque brian.lev722@gmail.com

## Acknowledgments

Our Grand Circus Instruction Team 

James Meredith, our main instructor

Dylan Gleason, our teaching assistant
