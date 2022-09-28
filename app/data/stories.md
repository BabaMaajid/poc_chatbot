## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
* permit
  - utter_Permit
* new_permit
 - utter_new_permit
* renew_permit
 - utter_renew_permit
* give_time
 - action_show_time
## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
