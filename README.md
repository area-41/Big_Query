# Big Query
###### Exemplos de uso prático do Big Query do Google, retirado do material utilizado durante o curso de Google Data Analytics.

### As consultas utilizam linguagem SQL para responder às questões abaixo:

### Questão:
![01_Big_Query_Exemplo_Texto_BabyName_Questao_Exercicio_UPLOAD_01](https://github.com/area-41/Big_Query/assets/87396846/fa738c65-e2e4-4ee4-8e17-7d214caaa462)

### Resposta:

SELECT name, count</br>
FROM 'industrial-gist-395320.babynames.names_2014'</br>
WHERE gender = 'M'</br>
ORDER BY count</br>
DESC LIMIT 5</br>

![02_Big_Query_Exemplo_Texto_BabyName_Questao_Exercicio_UPLOAD_02](https://github.com/area-41/Big_Query/assets/87396846/1a6b3459-13f6-4ce8-b7f8-35deb82bad32)



### Questão:
![03_Big_Query_Exemplo_Texto_BabyName_Questao_Exercicio_UPLOAD_01](https://github.com/area-41/Big_Query/assets/87396846/3e4657c9-a007-4a4e-b68e-f90bd8912c47)

### Resposta:

SELECT end_station_name</br>
FROM 'bigquery-public-data.london_bicycles.cycle_hire'</br>
WHERE rental_id = 57635395</br>
LIMIT 1000</br>

![04_Big_Query_Exemplo_Texto_BabyName_Questao_Exercicio_UPLOAD_02](https://github.com/area-41/Big_Query/assets/87396846/adcb0199-41a9-499b-a194-f0150560aded)
