CREATE TABLE users(
user_id INTEGER NOT NULL,
firstname VARCHAR NOT NULL,
lastname VARCHAR NOT NULL,
email VARCHAR NOT NULL,
password VARCHAR NOT NULL
);

INSERT INTO schedules (user_id, day, start_at, end_at) VALUES
(0, 1,'2PM', '4PM'),
(0, 2,'2PM', '4PM'),
(0, 3,'2PM', '4PM'),
(2, 5,'8aM', '6PM');

INSERT INTO users (user_id, firstname, lastname, email, password ) VALUES
(1, 'James', 'Bond', 'james.bond@gmail.com', 'one'),
(2, 'G', 'Ali', 'gali@gmail.com', 'two'),
(3, 'Nana', 'Bla', 'Nana@gmail.com', 'three');
