 # Estrutura de projeto TDSP, Templates para Documentos e Artefatos

Esse é uma estrutura de diretórios para projetos de Team Data Science Process desenvolvida pela Microsoft. Também contém templates para vários documentos que são recomendados ao executar projetos de ciência de dados usando TDSP.

[Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/overview) é uma metodologia para projetos de ciência de dados ágil e iterativa, desenvolvida para melhorar a colaboração e aprendizagem de equipes. Utiliza definições de ciclo de vida, uma estrutura padrão de projeto, artefatos e templates, além de [ferramentas](https://github.com/Azure/Azure-TDSP-Utilities) para aumentar a produtividade do projeto.

**OBSERVAÇÃO:** Nessa estrutura de diretório, a pasta ***dados* não deve conter arquivos GRANDES, sejam eles processados ou não-processados**. A pasta deve conter apenas **pequenas amostragens** do conjunto de dados, que podem ser utilizados para testar o código.

Os documentos [Documentação Inicial](./documentos/projeto/documentacao_inicial.md) e [Documentação Final](./documentos/projeto/documentacao_final.md), que se encontram dentro no caminho *documentos/projeto*, tem importância particular a ser considerada. Eles ajudam a definir o projeto ao início de uma iniciativa e fornecem a documentação final ao cliente ou área de negócio.


**OBSERVAÇÃO:** Em projetos de curto prazo, como provas de conceito (PoC) ou provas de valor (PoV), a criação de todos os documentos e artefatos recomendados pode levar um tempo considerável. Nesses casos, pelo menos as documentações iniciais e finais devem ser criadas e entregues ao cliente ou área de negócio. Conforme necessário, organizações podem modificar determinadas seções dos documentos. Contudo, é recomendável que o conteúdo dos documentos sejam mantidos, já que fornecem informações importantes sobre o projeto e entregáveis. 