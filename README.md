# Documenta-o-sistema-cloud
## AWS
O intuito desse sistema é armazenar o histórico escolar e sempre que um aluno antigo vier solicitar o histórico ele fica armazenado.
## Serviços usados:
### S3 – Para armazenar os dados de forma assíncrona, armazenamento de arquivos.
### S3 Glacier – Ira armazenar os históricos escolares mais antigos, podendo ser recuperado a qualquer momento.
### Lambda – Será usado para leitura das informações.
### RDS – Um banco de dados relacional que vai dar uma segurança para armazenar as informações dos alunos.

![Diagrama histórico escolar](https://github.com/LarissaRodrigues99/Documenta-o-AWS/blob/main/Imagens/Diagrama%20-%20hist%C3%B3rico%20escolar.png)