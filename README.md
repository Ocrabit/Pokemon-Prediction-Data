# Pokemon-Prediction-Data

### [Google Colab Link](https://colab.research.google.com/drive/17-XhZfBzx17Q95SJ4DGMkYjGuVWc_Gsk)

### [Presentation Link](https://www.canva.com/design/DAGDJh8okvQ/kjFWM35OT6cwqR05IxT54w/edit?utm_content=DAGDJh8okvQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## Data Dictionary
df_pokemon:
* '#' --> (Integer) Pokedex Num
* 'Name' --> (String) Name of Pokemon
* 'Type 1' --> (String) 1st Element Type of Pokemon
* 'Type 2' --> (String) 2nd Element Type of Pokemon
* 'HP' --> (Integer) Health Stat
* 'Attack' --> (Integer) Attack Stat
* 'Defense' --> (Integer) Defense Stat
* 'Speed' --> (Integer) Speed Stat
* 'Generation' --> (Integer) Which generation of Pokemon it is in
* 'Legendary' --> (Boolean) If the Pokemon is legendary or not

df_combats:
* 'First_pokemon' --> (Intger) The Pokedex number of the Pokemon who has the initial move in the battle
* 'Second_pokemon' --> (Intger) The Pokedex number of the Pokemon who defends first
* 'Winner' --> (Integer) The Pokedex number of the Pokemon who wins the battle
* 'WinnerBinary' --> (Boolean/Integer) Only contains 0 or 1s. A column added later in the code, when we convert the 'Winner' column into a (0 or a 1) which is read as (False or True). If the pokemon with the initial turn wins it is marked as a 1 else it is marked as a 0

---
## Enjoy The Project
