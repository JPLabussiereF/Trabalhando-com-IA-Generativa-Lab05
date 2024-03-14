# Processo, insights e possibilidades aprendidas durante o conteúdo **"Explorando os Recursos de IA Generativa com Copilot e OpenAI"**

## **1. IA generativa com o Microsoft Copilot**

### **- Introdução**

Inteligência Artificial Generativa (IAG) refere-se a sistemas de IA capazes de gerar novos conteúdos, como imagens, músicas, textos ou até mesmo vídeos, de forma autônoma. Em contraste com sistemas de IA que são usados principalmente para classificação ou previsão, os modelos generativos são projetados para criar novos dados que se assemelham ao que foi usado para treiná-los. Esses sistemas geralmente são baseados em redes neurais profundas, como as Redes Neurais Generativas Adversariais (GANs), Redes Neurais Autoregressivas (RNNs) e Transformadores.

Eles são aplicados em uma variedade de campos, incluindo arte, design, música, escrita criativa e até mesmo na geração de rostos realistas. A IAG levanta questões éticas, como autoria, originalidade e a possível disseminação de informações falsas ou manipuladas. No entanto, também oferece oportunidades emocionantes para a criação de conteúdo inovador e personalizado.

### **- Exemplos propostos com o Microsoft Copilot**

- **Usando prompts para gerar respostas**

Após abrir o [copilot.microsoft.com](https://copilot.microsoft.com/), podemos ver na parte inferior da tela uma janela, onde está escrito **"Pergunte-me qualquer coisa."** Através dela, à medida que você insere prompts, o Copilot usa todo o ***thread*** da conversa para retornar respostas. 

**Prompts usados:**

1° Prompt:
![Prompt 1](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/GenerateResponses1.png?raw=true)

2° Prompt:
![Prompt 2](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/GenerateResponses2.png?raw=true)

3° Prompt:
![Prompt 3](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/GenerateResponses3.png?raw=true)

**Respostas dos prompts:**

1° Resposta:
![Resposta 1](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/Responses1.png?raw=true)

2° Resposta:
![Resposta 2](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/Responses2.png?raw=true)

3° Resposta:
![Resposta 3](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/Responses3.png?raw=true)

- **Geração de imagens**

**Prompt usado:**

![Prompt usado para imagem](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/ImageGeneration.png?raw=true)

**Resposta do Prompt:**

![Resposta do Prompt de imagem](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/ImageGenerationResponse.png?raw=true)

- Geração de código

**Prompts usados:**

1° Prompt:
![Prompt usado para o 1° Código](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/CodeGeneration1.png?raw=true)

2° Prompt:
![Prompt usado para o 2° Código](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Inputs/CodeGeneration2.png?raw=true)

**Respostas dos Prompts:**

1° Resposta:
![Resposta do Prompt de Código 1](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/CodeGenerationResponse.png?raw=true)

2° Resposta:
![Resposta do Prompt de Código 2](https://github.com/JPLabussiereF/Trabalhando-com-IA-Generativa-Lab05/blob/main/Praticas/generativeAIwithMicrosoftCopilot/Outputs/CodeGenerationResponse2.png?raw=true)

## **2. Azure OpenAI**

O Azure OpenAI Service traz os modelos generativos de IA desenvolvidos pela OpenAI para a plataforma Azure, permitindo-lhe desenvolver soluções poderosas de IA que beneficiam da segurança, escalabilidade e integração de serviços fornecidos pela plataforma de nuvem Azure.

Você precisará de uma assinatura do Azure aprovada para acesso ao serviço Azure OpenAI para modelos de texto e código e modelos de geração de imagens DALL-E.

- Para se inscrever para uma assinatura gratuita do Azure, visite https://azure.microsoft.com/free.
- Para solicitar acesso ao serviço Azure OpenAI, visite https://aka.ms/oaiapply.

## **3. Filtros de conteúdo no Azure OpenAI**

O Azure OpenAI inclui filtros de conteúdo padrão para ajudar a garantir que solicitações e conclusões potencialmente prejudiciais sejam identificadas e removidas das interações com o serviço. Além disso, você pode solicitar permissão para definir filtros de conteúdo personalizados para suas necessidades específicas, a fim de garantir que as implantações de seu modelo imponham os princípios de IA responsáveis ​​apropriados para seu cenário de IA generativa. A filtragem de conteúdo é um elemento de uma abordagem eficaz para IA responsável ao trabalhar com modelos de IA generativos.

Você precisará de uma assinatura do Azure aprovada para acesso ao serviço Azure OpenAI.

- Para se inscrever para uma assinatura gratuita do Azure, visite https://azure.microsoft.com/free.
- Para solicitar acesso ao serviço Azure OpenAI, visite https://aka.ms/oaiapply.


## **Referências**

 - [DIO - Microsoft Azure AI Fundamentals](https://web.dio.me/track/a088cda7-a37f-451a-b392-46fa7e6ddc55)

 - [Explore generative AI with Microsoft Copilot](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)

 - [Explore Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)

 - [Explore content filters in Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html)



