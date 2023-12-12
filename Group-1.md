1. Contare quanti iscritti ci sono stati ogni anno

SELECT YEAR(`enrolment_date`) AS `enrolment_year`, COUNT(*) AS `number_of_enrolments` FROM `students` GROUP BY YEAR(`enrolment_date`);