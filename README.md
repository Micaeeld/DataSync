# DataSync

DataSync é um projeto real de integração e análise de dados de saúde em 31 servidores utilizando Python e SQL. O objetivo principal deste projeto é automatizar a extração, limpeza e armazenamento de dados de diferentes fontes de dados em um ambiente de saúde.

## Funcionalidades Principais

- **Extração de Dados**: Utilização de conexões SQL para extrair dados de 31 servidores diferentes, cada um contendo informações específicas relacionadas à saúde.

- **Limpeza e Transformação de Dados**: Assegura que os dados extraídos sejam limpos e transformados adequadamente para análise posterior. Inclui funções para categorizar doenças, ajustar valores de idade e renomear valores de questões e riscos.

- **Armazenamento de Dados**: Os resultados das consultas são armazenados em um arquivo Excel estruturado, com abas separadas por tipo de informação (clientes ativos, consultas, questões, riscos, entre outros).

## Tecnologias Utilizadas

- **Python**: Para manipulação e análise de dados, utilizando bibliotecas como Pandas para manipulação de dados estruturados e Openpyxl para manipulação de arquivos Excel.
  
- **SQL**: Para consulta e integração de dados de múltiplos servidores usando Pyodbc como conector.


## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias, reportar bugs ou implementar novas funcionalidades através de issues ou pull requests.
