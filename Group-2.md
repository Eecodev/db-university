2. Contare gli insegnanti che hanno l'ufficio nello stesso edificio

SELECT `office_address`, `office_number`, COUNT(*) AS `number_of_teachers` FROM `teachers` GROUP BY `office_address`, `office_number`;