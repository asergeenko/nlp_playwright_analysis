# Playwright Analysis using NLP
This is an approach to analyse theatre playwrights using simple NLP techniques like word embedings.

## Contents
### Parser
Parser produces CSV files from playwright content in FB2 format. 
### Dataset
To try our approach we analyse several Anton Chekhov plays, produced using our parser.

#### Data structure (sample from the Act I of ["The Seagull"](https://en.wikipedia.org/wiki/The_Seagull) by Anton Chekhov):
| act    | character | text |
| -------- | ------- |-----------|
| 1  | Сорин    | Кстати, скажи, пожалуйста, что за человек этот беллетрист? Не поймешь его. Все молчит.| 
| 1 | Треплев     | Человек умный, простой, немножко, знаешь, меланхоличный. Очень порядочный. Сорок лет будет ему еще не скоро, но он уже знаменит и сыт по горло… Что касается его писаний, то… как тебе сказать? Мило, талантливо… но… после Толстого или Зола не захочешь читать Тригорина.|
| 1    | Сорин    | А я, брат, люблю литераторов. Когда-то я страстно хотел двух вещей: хотел жениться и хотел стать литератором, но не удалось ни то, ни другое. Да. И маленьким литератором приятно быть, в конце концов.| 

- **act** - number of the act
- **character** - current character
- **text** - character text

