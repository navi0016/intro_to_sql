[See assignment in Alexa.](https://alexa.bitmaker.co/cohorts/72/assignments/2244/latest)

SELECT * FROM robots WHERE source = 'Star Wars';

SELECT * FROM robots WHERE personality ='anxious';

SELECT * FROM recipes where nut_free ='true';

SELECT COUNT(*) FROM recipes where gluten_free =true;

SELECT COUNT(*) FROM recipes where gluten_free =true AND vegetarian =false;

SELECT name FROM animals where number_of_legs=(SELECT MAX(number_of_legs) from animals);

SELECT name FROM board_games where mins_to_play=(SELECT MIN(mins_to_play) FROM board_games);

SELECT name FROM recipes WHERE minutes_required=(SELECT MAX(minutes_required) FROM recipes);

SELECT name FROM robots WHERE name LIKE 'M%';

SELECT COUNT(*) FROM board_games WHERE max_players =8;

SELECT * FROM animals WHERE swimming = true AND egg_laying = true;

 SELECT * FROM animals WHERE swimming = true AND egg_laying = true AND flying = false;

 SELECT name FROM board_games where max_players =(SELECT MAX(max_players) FROM board_games);
