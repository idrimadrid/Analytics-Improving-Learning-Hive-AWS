**Exemple de création d’une table dans la base de donne Mysql:

create	table	courses	(	code_module	varchar(20),	code_presentation	varchar(20),	module_presentation_length	int);

**Ajout de la clé primaire:

alter table courses add column `id` int(10) unsigned primary KEY AUTO_INCREMENT;



**Chargement des fichiers CSV:

LOAD DATA INFILE '/home/cloudera/Desktop/dataset/1courses.csv' INTO TABLE courses FIELDS TERMINATED BY ',' LINES TERMINATED BY '\n';

**Importation de la table vers HDFS:

sqoop import --connect jdbc:mysql://localhost/students --table courses --username root -P --target-dir students_database/courses
