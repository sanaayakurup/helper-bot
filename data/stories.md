## ideal path
* greet
  - utter_ask
* query_entity
  - action_query_knowledge_base
* affirm
  - utter_ask_again
* deny
  - utter_goodbye

## ideal path 2
* greet
  - utter_ask
* query_entity
  - action_query_knowledge_base
  - utter_ask_again
* affirm
* query_entity
  - action_query_knowledge_base
  - utter_ask_again
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye
