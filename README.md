# Faker

- Створення проєкту

mkdir EX-08
cd EX-08
python -m venv venv
cd venv/scripts
venv/scripts >>> activate

- Створення скрипту із таблицями БД

cd /c/Users/user/Documents/GitHub/Faker/EX-08/

salary.sql

- Створення таблиць БД

create_db.py

- Виконання скрипту

python create_db.py

- Наповнення БД даними

python fill_data.py

- Виконання запитів до БД

  1.Знаходження середньої зарплати за посадами

python select_first.py

[(5943.57, 'Editor, commissioning'), (6164.81, 'Industrial buyer'), (4147.83, 'Materials engineer'), (5418.43, 'Research scientist (medical)'), (5121.77, 'Surveyor, insurance')]

2.Вибірка: кількість співробітників за компаніями

python select_second.py

[(9, 'Solis, Taylor and Mckee'), (12, 'King, Brock and Johnson'), (9, 'Moran Group')]

3.Вибір співробітників компаній, у яких у 7 місяців була зарплата > 5000

python select_third.py

[('Solis, Taylor and Mckee', 'Bethany Myers', 'Surveyor, insurance', 9594), ('Solis, Taylor and Mckee', 'Crystal Wilson', 'Surveyor, insurance', 6908), ('Solis, Taylor and Mckee', 'Jennifer Smith', 'Editor, commissioning', 6407), ('King, Brock and Johnson', 'Amanda Fowler', 'Research scientist (medical)', 9804), ('King, Brock and Johnson', 'Anne Moore', 'Industrial buyer', 9800), ('King, Brock and Johnson', 'Craig Byrd', 'Industrial buyer', 5866), ('King, Brock and Johnson', 'David Davis', 'Research scientist (medical)', 6189), ('King, Brock and Johnson', 'Elizabeth Rojas', 'Industrial buyer', 7612), ('King, Brock and Johnson', 'Peter Butler', 'Materials engineer', 5392), ('King, Brock and Johnson', 'Sharon Duncan', 'Industrial buyer', 9751), ('King, Brock and Johnson', 'Taylor Gilbert', 'Editor, commissioning', 5431), ('King, Brock and Johnson', 'Timothy Ramirez', 'Editor, commissioning', 6695), ('Moran Group', 'David Santos', 'Industrial buyer', 9301), ('Moran Group', 'Dennis Wood', 'Editor, commissioning', 9904), ('Moran Group', 'Diane Roberts', 'Editor, commissioning', 8151), ('Moran Group', 'John Gardner', 'Industrial buyer', 5008), ('Moran Group', 'Michael Manning', 'Research scientist (medical)', 6355), ('Moran Group', 'Rodney Cooper', 'Industrial buyer', 5415), ('Moran Group', 'Sandra Castillo MD', 'Industrial buyer', 7490)]
