# Curso de ChatBot part. 1

Curso inicial focado em ensinar a estrutura da IBM Watson Assistant com criação de um chatbot para responder perguntas básicas.

Introdução a Intents (intenções), Entities (Entidades) e Dialog (Dialogos), com estruturação de conversa, além de organização,
fluxo de conversa e respostas com entidades e intenções.

- **Intenções:** objetivos que você espera que seus usuários tenham quando interagirem com seu assistente. Defina uma intenção para cada objetivo que pode ser identificado em uma entrada do usuário. Por exemplo, é possível definir uma intenção denominada store_hours que responde às perguntas sobre os horários da loja. Para cada intenção, você inclui elocuções de amostra que refletem a entrada que os clientes podem usar para perguntar as informações de que eles precisam, como **Que horas vocês abrem?**

- **Entidades:** uma entidade representa um termo ou objeto que fornece contexto para uma intenção. Por exemplo, uma entidade pode ser um nome de cidade que ajuda seu diálogo a distinguir para qual loja o usuário quer saber os horários da loja. Depois de incluir entidades, atualize seu diálogo para usá-las. Inclua nós de diálogo que manipulem as muitas possíveis permutações de uma solicitação com base nas entidades localizadas na entrada do usuário.

- **Diálogo:** use a ferramenta de diálogo para construir um fluxo de diálogo que incorpora suas intenções. O fluxo de diálogo é representado graficamente na ferramenta como uma árvore. É possível incluir uma ramificação para processar cada uma das intenções que você deseja que seja manipulada por seu assistente.

À medida que você inclui dados de treinamento, um classificador de língua natural é incluído automaticamente na qualificação. O modelo do classificador é treinado para entender os tipos de solicitações que você ensina seu assistente a atender e responder.

Para mais informações [IBM Watson DOCs](https://cloud.ibm.com/docs/assistant-data?topic=assistant-data-getting-started)