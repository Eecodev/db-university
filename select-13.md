13. Selezionare tutti gli appelli d'esame che avvengono nel pomeriggio (dopo le 14) del 20/06/2020 (21)

SELECT * FROM `exams` WHERE DATE(`date`) = '2020-06-20' AND HOUR(`hour`) >= 14;