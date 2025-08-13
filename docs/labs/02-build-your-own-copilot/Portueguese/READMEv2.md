# Crie aplicações inteligentes com a pilha Copilot da Microsoft e Azure OpenAI

## Duração Total Estimada: 4 horas

## Visão geral do workshop

Neste laboratório, irá adquirir uma compreensão sólida dos fundamentos da IA generativa, do Azure OpenAI, dos padrões de Geração Aumentada por Recuperação (RAG), do Semantic Kernel e de como utilizar estes conceitos para criar o seu próprio Copilot para as necessidades do seu negócio. Irá também explorar casos de utilização que demonstram experiências de produtos Copilot. Utilizando a pilha Copilot da Microsoft e casos de utilização práticos, este laboratório irá guiá-lo na conceção e criação de sistemas inteligentes que integrem modelos de base, resultando num aumento da produtividade e em experiências de produto hiperpersonalizadas.

## Objetivo

- **Verificar e obter os valores dos recursos do Azure:** Este exercício prático tem como objetivo verificar e obter os valores para garantir a configuração e a conectividade corretas dos recursos do Azure.

- **Executar a aplicação Miyagi localmente:** Este exercício prático tem como objetivo configurar a aplicação Miyagi, implementar o serviço de recomendações, implementar o frontend localmente, otimizar a recuperação de dados com o Azure AI Search e explorar a aplicação e o serviço para uma experiência de utilizador personalizada.

- **Contentorizar a interface Miyagi e o serviço de recomendações para o Azure Kubernetes Service (AKS):** Este exercício prático tem como objetivo contentorizar e implementar a interface Miyagi e o serviço de recomendações no AKS, configurar o Kubernetes, enviar imagens Docker para o Azure Container Registry (ACR) e verificar a implementação através dos endpoints do serviço.

- **Explorar e verificar a interface Miyagi e o serviço de recomendações contentorizados no AKS:** Este exercício prático tem como objetivo implementar e verificar a interface Miyagi e o serviço de recomendações no AKS, testar APIs e aceder à interface através dos endpoints do Ingress para garantir a funcionalidade. Este exercício reforça a compreensão da gestão e do encaminhamento de tráfego em ambientes Kubernetes.

- **Expor o Azure OpenAI através do APIM:** Este exercício prático tem como objetivo verificar e criar APIs no serviço API Management para atualizar a imagem Docker do serviço de recomendações, garantindo a otimização e manutenção de aplicações contentorizadas.

- **Introdução à criação do seu próprio Copilot:** Este exercício prático tem como objetivo integrar Modelos de Linguagem de Grande Escala (LLMs) com linguagens como C#, Python e Java, permitindo a criação de plugins facilmente encadeáveis.

## Pré-requisitos

Os participantes devem ter:

- Compreensão dos fundamentos de IA generativa

- Familiaridade com o Azure OpenAI

- Experiência com o Semantic Kernel

### Arquitetura

A arquitetura do Miyagi utiliza IA para interações de utilizador hiperpersonalizadas, transformando aplicações com competências do Semantic Kernel e engenharia de prompts avançada. Apresenta microsserviços escaláveis e uma espinha dorsal orientada a eventos, evoluindo com novos modelos de IA. O frontend oferece experiências personalizadas semelhantes ao Microsoft Copilot.

Integra Azure Functions, AKS e Apache Kafka para uma comunicação fluida, com os dados geridos pelo Cosmos DB e pelo Azure Storage. O Miyagi exemplifica a utilização avançada de IA e de serviços Azure para aplicações inteligentes preparadas para o futuro.

#### Diagrama de Arquitetura

> Update the arch diagram

### Explicação dos Componentes

A arquitetura deste laboratório envolve os seguintes componentes principais:

- **Azure OpenAI:** Integra os modelos de linguagem da OpenAI na nuvem Microsoft Azure, permitindo soluções de IA escaláveis para processamento de linguagem natural e automação.

- **AI Search:** Serviço de nuvem que oferece recursos poderosos e flexíveis de pesquisa, incluindo pesquisa de texto completo e funcionalidades aprimoradas por IA.

- **Azure Functions:** Executa código em resposta a eventos sem a necessidade de gerenciar servidores. Escala automaticamente de acordo com a demanda.

- **AKS (Azure Kubernetes Service):** Serviço Kubernetes gerenciado para orquestração e escalonamento de contêineres.

- **Apache Kafka:** Gerencia o streaming de dados em tempo real e o processamento de eventos.

- **Cosmos DB:** Banco de dados distribuído globalmente, multi-modelo, com baixa latência e alta disponibilidade.

- **Azure Storage:** Armazenamento escalável para blobs, arquivos, filas e tabelas.

- **Bing Search:** Permite adicionar recursos de pesquisa do Bing aos seus aplicativos, oferecendo APIs para pesquisas na web, imagens, vídeos e notícias.

> Important message

> Support Contact
