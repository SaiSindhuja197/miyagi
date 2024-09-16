# Crie aplicações inteligentes com a pilha Copilot da Microsoft e Azure OpenAI

## Visão geral do workshop

Neste workshop, obterá uma forte compreensão dos conceitos básicos de IA generativa, Azure Open AI, padrões de geração aumentada de recuperação (RAG), kernel semântico e como utilizar estes conceitos para criar o seu próprio copiloto para as suas necessidades de negócio. Explorará também casos de utilização que mostram experiências de produtos Copilot. Utilizando a pilha Copilot da Microsoft e casos de utilização práticos, este workshop irá guiá-lo na visão e criação de sistemas inteligentes que integram modelos básicos, resultando em maior produtividade e experiências de produto hiperpersonalizadas.

### O que esperar?

Aprenda conceitos:

O primeiro segmento do workshop envolve uma apresentação que lhe fornecerá uma base sólida nos conceitos de IA generativa e o guiará no processo de criação do seu próprio copiloto utilizando a pilha Microsoft Copilot.

## Laboratório prático:

No segmento prático (que será a maior parte deste workshop), os participantes terão uma exposição profunda às características do Copilot Stack, especialmente com o Kernel Semântico, a Prompt Engineering e a Azure Cognitive Search. Durante esta parte do laboratório prático, irá clonar um exemplo de aplicação de Consultor de Investimentos e implantá-lo no Azure. Esta aplicação aproveita o poder do Azure Open AI, RAG, Semantic Kernel e outros serviços Azure. Explorará os seguintes recursos principais e obterá insights sobre os mecanismos subjacentes:

Copiloto do Consultor de Investimentos: Este Copiloto, desenvolvido com IA Generativa, fornece recomendações de investimento com base nas preferências do utilizador. Utiliza Azure Open AI, Semantic Kernel, Azure Cognitive Search (com indexação vetorial para incorporações), Azure Cosmos DB, Container Apps e Azure API Management.

Copiloto de chat: obtenha assistência em tempo real com investimentos utilizando esta funcionalidade. Tira partido do Azure Open AI, do Semantic Kernel, do Azure Cognitive Search (com indexação vetorial para incorporações), do Azure Cosmos DB, das Container Apps e do Azure API Management.

### Projecto Miyagi – Exemplo de previsão para [copilot stack](https://learn.microsoft.com/en-us/semantic-kernel/overview/#semantic-kernel-is-at-the-center-of- o -copiloto-stack)

O Projecto Miyagi apresenta o Copilot Stack da Microsoft num [workshop de visão](https://github.com/Azure-Samples/intelligent-app-workshop) destinado a conceber, desenvolver e implementar aplicações inteligentes de nível empresarial. Ao explorar [casos de utilização] de ML generativo e tradicional (https://iappwksp.com/wksp/05-use-cases/), a Miyagi oferece uma abordagem experiencial para o desenvolvimento de experiências de produtos com IA que aumentam a produtividade e permitem a hiperpersonalização . Além disso, o workshop apresenta aos engenheiros de software tradicionais padrões de design emergentes em engenharia imediata, como a cadeia de pensamento e o aumento da recuperação, bem como técnicas como a vetorização para memória de longo prazo, o ajuste fino de modelos OSS e plug-ins. ferramentas para aumentar e aterrar LLMs.

O projeto inclui exemplos de utilização do [Kernel Semântico](https://learn.microsoft.com/en-us/semantic-kernel/overview/#semantic-kernel-is-at-the-center-of-the-copilot -stack), [Promptflow](https://promptflow.azurewebsites.net/overview-what-is-prompt-flow.html), [LlamaIndex](https://github.com/jerryjliu/llama_index), [LangChain ](https://github.com/hwchase17/langchain#readme), lojas de vetores ([Azure Cognitive Search](https://github.com/Azure/cognitive-search-vector-pr), [CosmosDB Postgres pgvector ] (https://learn.microsoft.com/en-us/azure/cosmos-db/postgresql/howto-use-pgvector) e utilitários de imagem generativos, como o [DreamFusion](https://huggingface.co/thegovind / reddogpillmodel512) e [ControlNet](https://github.com/lllyasviel/ControlNet). . e ajuste os seus dados privados para criar os seus próprios copilotos.

Esta base de código poliglota depende de uma infinidade de micro-serviços, implementando vários [casos de uso](https://iappwksp.com/wksp/05-use-cases/) utilizando a nossa pilha Copilot. Inclui texto e imagens generativas para treino financeiro personalizado, resumo e orquestração semelhante a um agente. Construído num backbone de arquitetura dividida em eventos (EDA) nativo da cloud, o design e a base de código garantem atributos de qualidade de nível empresarial, como disponibilidade, escalabilidade e facilidade de manutenção.

Embarque numa viagem para transformar as suas aplicações em sistemas inteligentes e de ponta com o workshop autoguiado e descubra a arte do possível.

### Front-end
A interação com modelos básicos é mais do que chat. Este exemplo mostra alguns casos de utilização

![frontend](../Media/wip-ui.png)

### Arquitetura

#### Arquitetura lógica de alto nível

![azure](../Media/wip-azure.png)

#### Orquestração Kernel Semântico para o caso de uso Miyagi

![sk-orchestration](../Media/sk-memory-orchestration.png)

#### Vista de 30 mil pés

![pilha copiloto](../Media/basic-arch.png)

### Pilha de copiloto

![pilha copiloto](../Media/copilot-stack.png)

### Serviços e capacidades

- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/concepts/models)
  - gpt-4
  - gpt-35-turbo
  - text-embedding-ada-002
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel)
- [Use your own data with Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=command-line&pivots=rest-api#example-curl-commands)
- [AzureML PromptFlow](https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/overview-what-is-prompt-flow?view=azureml-api-2)
- [TypeChat](https://microsoft.github.io/TypeChat)
- [Azure Functions](https://azure.microsoft.com/en-ca/products/functions/)
- [APIM](https://learn.microsoft.com/en-us/azure/api-management/)
- [Service Bus](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview)
- [Event Grid](https://learn.microsoft.com/en-us/azure/event-grid/overview)
- [Logic Apps](https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
- [Cosmos DB](https://azure.microsoft.com/en-us/products/cosmos-db/)
- [Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/)
- [Azure Storage](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- [LangChain](https://github.com/hwchase17/langchain#readme)
- [Foundation Models from CogServices](https://azure.microsoft.com/en-us/blog/announcing-a-renaissance-in-computer-vision-ai-with-microsofts-florence-foundation-model/)
- [Qdrant](https://qdrant.tech/solutions/)
- [Microsoft DeepSpeed Chat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat)
- [Azure Web PubSub](https://azure.microsoft.com/en-us/products/web-pubsub)
- [Azure Communication Services (ACS)](https://learn.microsoft.com/en-us/azure/communication-services/overview#common-scenarios)

## Resumo

### Introdução à criação de aplicações inteligentes com a pilha Copilot da Microsoft e o Azure OpenAI

### Introdução ao ambiente CloudLabs

### Laboratório 1 - Execute localmente a aplicação Miyagi

Neste laboratório, o foco está na configuração da aplicação Miyagi para prontidão operacional. Posteriormente, a atenção passa para a compreensão da implementação diferenciada do serviço de recomendação. A fase prática envolve a execução do serviço de recomendação e a implementação local do frontend Miyagi para teste e desenvolvimento.

### Laboratório 2.1: Contentorização da UI Miyagi e do serviço de recomendação para o Azure Kubernetes Service (AKS)

Neste laboratório, irá criar as imagens Docker e publicá-las no Azure Kubernetes Service (AKS).

### Laboratório 3 – Expor o OpenAI através do serviço de gestão de API

Neste laboratório, irá verificar e criar APIs no serviço de gestão de APIs implementado para atualizar a imagem do Docker para o serviço de recomendação. A revisão do serviço de recomendação do Container App encapsula a abordagem meticulosa para manter e otimizar as aplicações contentorizadas dentro do âmbito do projeto.

### Primeiros passos com o seu próprio copiloto

Neste laboratório, irá criar a sua própria aplicação Copilot utilizando Semantic Kernal Tools. Além disso, irá configurar o Azure AI Search.
