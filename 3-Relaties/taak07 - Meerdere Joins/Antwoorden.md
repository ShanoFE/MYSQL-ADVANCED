# Antwoorden

1. Copy paste je gemaakte SQL query hieronder
SELECT game.name, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id
LEFT JOIN genre ON game.genre_id = genre.id WHERE game.name LIKE "b%";
2. Copy paste je gemaakte SQL query hieronder
Copy paste je gemaakte SQL query hieronder
SELECT game.name, platform.platform, publisher.publisher FROM game LEFT JOIN platform ON game.platform_id = platform.id
LEFT JOIN genre ON game.genre_id = genre.id WHERE game.year=2013;
3. Copy paste je gemaakte SQL query hieronder
SELECT game.name, game.global_sales, platform.platform, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id
LEFT JOIN genre ON game.genre_id = genre.id WHERE genre.genre="Puzzle" AND WHERE game.year > 2000;
4. Copy paste je gemaakte SQL query hieronder
Copy paste je gemaakte SQL query hieronder
SELECT game.year, game.jp_sales, platform.platform, publisher.publisher, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id
LEFT JOIN genre ON game.genre_id = genre.id LIKE "Mario%";
5. Copy paste je gemaakte SQL query hieronder
SELECT game.year, game.name, platform.platform, publisher.publisher, genre.genre FROM game LEFT JOIN platform ON game.platform_id = platform.id
LEFT JOIN genre ON WHERE platform.platform="PC";