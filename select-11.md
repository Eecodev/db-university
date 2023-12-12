11. Selezionare tuttigli studenti che hanno più di 30 anni

SELECT * FROM `students` WHERE YEAR(CURRENT_DATE) - YEAR(date_of_birth) > 30;