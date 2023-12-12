3. Calcolare la media dei voti di ogni appello d'esame

SELECT `exam_id`, AVG(`vote`) AS `average_mark` FROM `exam_student` GROUP BY `exam_id`;