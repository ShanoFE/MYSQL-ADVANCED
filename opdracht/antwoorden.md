# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT circuits.name, drivers.surname, driver_standing.points FROM circuits JOIN races ON circuits.circuitId = races.circuitId JOIN driver_standing ON races.raceId = driver_standing.raceId JOIN drivers ON driver_standing.driverId = drivers.driverId
2. Copy paste je gemaakte SQL query hieronder
   SELECT races.name, races.year, drivers.surname, driver_standing.points FROM races
   JOIN driver_standing
   ON races.raceId = driver_standing.raceId
   JOIN drivers
   ON driver_standing.driverId = drivers.driverId WHERE points = 10 AND year= "2017";
3. Copy paste je gemaakte SQL query hieronder
   SELECT drivers.forename, drivers.surname, pitstops.duration FROM drivers JOIN pitstops ON drivers.driverId = pitstops.driverId WHERE duration < 25
4. Copy paste je gemaakte SQL query hieronder
   SELECT constructors.name, races.name, races.year FROM constructors JOIN constructor_standing ON constructors.constructorId = constructor_standing.constructorStandingsId JOIN races ON constructor_standing.raceId = races.raceId WHERE constructors.name = "McLaren" AND year = 2018
5. Copy paste je gemaakte SQL query hieronder
   SELECT circuits.name, circuits.country, races.name, drivers.surname, races.year FROM circuitS JOIN races ON circuits.circuitId = races.circuitId JOIN driver_standing ON races.raceId = driver_standing.raceId JOIN drivers ON driver_standing.driverId = drivers.driverId WHERE races.year= 1950 AND drivers.surname LIKE 'f%'
