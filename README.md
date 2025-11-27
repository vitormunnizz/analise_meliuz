## Descrição do Projeto

Este projeto realiza uma análise detalhada dos dados de cashback, com foco em determinar a viabilidade de investimento por grupos de usuários. O processo inclui a limpeza de duplicatas, remoção de valores nulos e tratamento de outliers, com o objetivo principal de calcular o lucro e a porcentagem de cashback de cada grupo com base nos dados fornecidos.

A análise final busca identificar o grupo mais lucrativo, levando em consideração o cashback médio e o número de vendas realizadas.

## Funcionalidades

- Limpeza de dados: remoção de duplicatas e tratamento de valores nulos.
- Tratamento de outliers: utilização de métodos estatísticos para lidar com dados anômalos.
- Cálculo de métricas como lucro por grupo, número de vendas, comissão e cashback total.
- Visualização de dados para análise exploratória e comparativa entre grupos.
- Avaliação da viabilidade de diferentes estratégias de cashback.

## Requisitos

Antes de executar o projeto, é necessário garantir que seu ambiente tenha os seguintes requisitos instalados:

- **Python 3.7+**
- **Jupyter Notebook**
- **Bibliotecas Python necessárias**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn (opcional, para análises mais avançadas)

## Descrição da Base de Dados Agrupados

- **Grupos de Usuários**: Identificação dos diferentes grupos de clientes no dataset.
- **Compradores**: Número total de compradores em cada grupo.
- **Comissão**: Valor total da comissão obtida para cada grupo.
- **Cashback**: Total devolvido como cashback para os compradores em cada grupo.
- **Vendas Totais**: Total de vendas realizadas em cada grupo.
- **Porcentagem de Cashback**: Percentual do valor total das vendas devolvido como cashback.

## Resultados

A análise revelou os seguintes resultados:

- O cashback médio geral é de **5,84%**, com os seguintes percentuais por grupo:
  - Grupo 1: **4,16%**
  - Grupo 2: **5,78%**
  - Grupo 3: **7,38%**
  
- Em termos de vendas, os grupos apresentaram:
  - Grupo 1: **9.633 vendas**
  - Grupo 2: **10.460 vendas**
  - Grupo 3: **10.769 vendas**

- Para determinar a lucratividade de cada grupo, foi considerado o número de vendas e o cashback, resultando nos seguintes lucros:
  - Grupo 1: **R$ 404.715**
  - Grupo 2: **R$ 344.813**
  - Grupo 3: **R$ 251.559**

Conclusão: Apesar de o grupo 1 ter um menor número de vendas em relação aos outros grupos, o cashback mais baixo resultou em maior lucratividade. Assim, a taxa de **4,16% de cashback** é a mais vantajosa, gerando o maior lucro.

## 👨‍💻 Autor

**Vitor Hugo Muniz de Sousa Santos**

💼 Engenheiro da Computação | Desenvolvedor Front-end

📧 [vitormunnizzdev@gmail.com](mailto:vitormunnizzdev@gmail.com)
🌐 [www.linkedin.com/in/vitormunnizz](https://www.linkedin.com/in/vitormunnizz)

## 📝 Licença

Este projeto está licenciado sob a **MIT License**.
Sinta-se livre para usar e modificar conforme necessário, mantendo os créditos ao autor.

⭐ **Se este projeto te ajudou, deixe uma estrela no repositório!**```
