
<img src="https://github.com/NikUrs/Mykola_Ursalov/blob/50d36e144ddf75feda7971d8ee4a60230156cbfb/img/scheme.png" style="width: 50%;">

- Отобразить Имя, Фамилия, Дата регистрации, Уникальный ID с таблиц Clients, Certificates (используется left join)
SELECT NAME, SURNAME, REGISTER_DATE, FILE, UNIQUE_ID FROM CLIENTS
LEFT JOIN CERTIFICATES ON CLIENTS.ID = CERTIFICATES.USER_ID

- Сгруппировать студентов по курсам SELECT * FROM CLIENT_COURSE 
GROUP BY CLIENT_COURSE.COURSE_ID;

- Получить студентов, зарегистрированных 2023 года
SELECT * FROM CLIENTS WHERE REGISTER_DATE LIKE '2023%'

- Получить студентов, зарегистрированных после 2023-08-01 (международный формат записи)
SELECT * FROM CLIENTS WHERE REGISTER_DATE > '2023-08-01'

- Получить активных (незабаненных) студентов 
SELECT COUNT(IS_BANNED) FROM  CLIENTS 
HAVING IS_BANNED = FALSE;
