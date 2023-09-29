### DIO | PROJETO PYTHON

#### • 💻 O QUE FOI SOLICITADO

Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas 😎

Vocês já mergulharam a fundo no mundo da Ciência de Dados conosco! Juntos, construímos um pipeline ETL eficaz, começando com a simples extração de IDs de usuários de uma planilha, seguindo para uma transformação inovadora com a IA do GPT-4 da OpenAI, e culminando no carregamento desses dados transformados de volta ao 'Santander Dev Week 2023'. Agora, o desafio é reimaginar esse processo de ETL. Como vocês aplicariam o que aprenderam em um novo domínio de aplicação, sem depender diretamente de APIs externas (caso queiram simplificar)? Pensem nas infinitas possibilidades e domínios que podem ser explorados, e deixem a criatividade fluir!

#### • 💡 A SOLUÇÃO CRIADA

O cenário escolhido para a aplicação da ferramenta ocorreu em uma operadora de telefonia. Nesse contexto, havia dois conjuntos de dados essenciais: um relacionado aos clientes e seus respectivos planos, e outro contendo informações sobre aparelhos em oferta, válidos para todos os planos disponíveis.

Para abordar essa tarefa, adotei o Google Colab como ambiente de desenvolvimento e criei duas abordagens distintas no código. A primeira delas consistia em utilizar uma mensagem padronizada que poderia ser direcionada a todos os clientes, com ajustes apenas nos detalhes específicos dos produtos, clientes e planos. Essa abordagem foi projetada para atender às necessidades daqueles que não tinham acesso à API da OpenAI devido ao custo associado à sua utilização.

A segunda abordagem empregava um modelo de linguagem generativa para gerar mensagens personalizadas, adaptadas a cada cliente individualmente. Essa estratégia proporcionava uma maior personalização das mensagens, tornando-as mais eficazes em termos de comunicação.

Após a integração das informações das planilhas e a criação das mensagens personalizadas, seja através do modelo de linguagem generativa ou da abordagem "básica", o resultado era uma planilha em formato Excel, contendo as mensagens customizadas. Essa planilha podia então ser importada no software da empresa, facilitando o envio automatizado das mensagens via WhatsApp para os respectivos clientes.

Esse processo permitirá à operadora de telefonia melhorar a comunicação com seus clientes, apresentando ofertas relevantes de forma personalizada e eficiente.

[Clique aqui para abrir o projeto no Google Colab](https://colab.research.google.com/drive/1HcxODciPByexKP9ahfNzMKpyUc2nEjQ3?usp=sharing)


