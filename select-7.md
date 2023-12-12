7. Selezionare tutti gli appelli d'esame dei mesi di giugno e luglio 2020 (2634)

SELECT * FROM `exams` WHERE YEAR(`date`) = 2020 AND MONTH(`date`) IN (6,7);