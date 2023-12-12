4. Contare quanti corsi di laurea ci sono per ogni dipartimento

SELECT `department_id`, COUNT(*) AS `number_of_degrees` FROM `degrees` GROUP BY `department_id`;