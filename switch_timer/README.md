## Home Assistant Package

Simple package that can turn on, off or toggle according to the choosen Hour, Minute or Seconds.

---

Recently I added a relay to our Kettle and for safety when the water starts boiling the Kettle automatically turns OFF.
The time needed to boil depends on the quantity of water inside so I made this small package to decide how long it will ON before automatically turn the Relay OFF and made it universal for every entity.

---

## Configuration
1. At "input_select" "switch_timer_entities" rename Kettle, Light, TV to your choice and add more if you want.
2. In the automation "action" also fix the "data_template" to math your "input_select"

---

## To-Do List

1. work Alexa and Google Assistant (eg. when saying "...,Turn On kettle" starts with the timer instead of real entity
2. Add customize for renaming
3. fix readme
---
