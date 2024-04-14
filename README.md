# Cycling-Analytics-in-AWS
- Cycling data project made using aws Glue and Power BI
- Google Drive - Power BI and Dataset: https://drive.google.com/drive/folders/1TGVm_FLPf2Ok4ZF3uy2KyeYsAH6VqrrT?usp=sharing

# Indicadores e estatísticas do uso de bicicletas
##### Arquitetura de dados utilizada: Data Lake (Batch Processing) 
##### Tecnologias: AWS, GLUE, SQL, PYTHON, POWER BI

**Principais pontos do projeto:**
1. Dados foram coletados do Kaggle.
2. Armazenamento dos dados em ambiente cloud (AWS).
3. Processamento dos dados utilizando PySpark por meio do AWS Glue.
4. Tratamento dos dados e disponibilização em camadas (Raw, Trusted e Refined), podendo ser consumidas por outros usuários e áreas.
5. Criação de um dashboard analítico para facilitar a visualização das informações.

Dados disponíveis em:
- https://www.kaggle.com/datasets/rubyphan/bike-share?select=202208-divvy-tripdata.csv



##### Diagrama da Arquitetura de Dados (Data Lake):
![Batch Processing Pipeline](https://github.com/Igorps023/Cycling-Analytics-in-AWS/blob/main/Batch%20processing%20Glue%20Job.png?raw=true "Batch Processing Pipeline")


Os scripts e notebooks utilizados estão disponíveis nas respectivas pastas.

##### Dashboard feito em Power BI:
![Dashboard1](https://github.com/Igorps023/Cycling-Analytics-in-AWS/blob/main/Overview%201.jpg?raw=true "Dashboard1")
![Dashboard2](https://github.com/Igorps023/Cycling-Analytics-in-AWS/blob/main/Overview%202.jpg?raw=true "Dashboard2")

Arquivo .pbix está disponível para download. 
