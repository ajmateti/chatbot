

## story_1_1
* greet
   - utter_greet
   - utter_ask_name
* inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* deny
   - utter_goodbye

## story_1_2
* greet + inform{"name":"ajay"}
   - slot{"name":"ajay"}
   - utter_greet
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* deny
   - utter_goodbye
   
   
## story_1_3
* greetings_with_name{"name":"sachin"}
   - slot{"name":"ajay"}
   - utter_greet
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* deny
   - utter_goodbye
   
    

## story_2_1
* greet
   - utter_greet
   - utter_ask_name
* inform{"name":"spoorthi"}
   - slot{"name":"spoorthi"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_2_2
* greetings_with_name{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_2_3
* greet + inform{"name":"ajay"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye

## story_3_1
* greet
   - utter_greet
   - utter_ask_name
* inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_3_2
* greet + inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_greet
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_3_3
* greetings_with_name{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_greet
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
   
## story_4_1
* greet
   - utter_greet
   - utter_ask_name
* inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_4_2
* greet + inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_4_3
* greetings_with_name"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_5_1
* greet
   - utter_greet
   - utter_ask_name
* inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"running nose"}
   - slot{"symptom":"running nose"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_4_2
* greet + inform{"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"running nose"}
   - slot{"symptom":"running nose"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"headache"}
   - slot{"symptom":"headache"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"shivers"}
   - slot{"symptom":"shivers"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye
   
## story_5_3
* greetings_with_name"name":"aneesh"}
   - slot{"name":"aneesh"}
   - utter_introduction
* ask_for_diagnosis
   - action_ask_symptom
* say_symptoms{"symptom":"fever"}
   - slot{"symptom":"fever"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"running nose"}
   - slot{"symptom":"running nose"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"vomitings"}
   - slot{"symptom":"vomitings"}
   - action_save_symptom
   - action_ask_symptom
* say_symptoms{"symptom":"rashes"}
   - slot{"symptom":"rashes"}
   - action_save_symptom
   - action_ask_symptom
* deny
   - action_predict_disease
   - utter_goodbye