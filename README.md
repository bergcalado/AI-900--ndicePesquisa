# AI-900-IndicePesquisa
Explorar um índice de Pesquisa de IA (UI) do Azure
Neste resumo vamos criar:
-  Criar recursos do Azure.
- Extrair dados de uma fonte de dados.
- Enriqueça dados com habilidades de IA.
- Usar o indexador do Azure no portal do Azure.
- Consultar seu índice de pesquisa.
- Revisar resultados salvos em um Knowledge Store.

1º Passo: Criar um recurso de Pesquisa de IA do Azure.
Um recurso de Pesquisa de IA do Azure é uma parte da plataforma de serviços cognitivos da Microsoft Azure que oferece capacidades avançadas de pesquisa por meio de inteligência artificial (IA). Ele permite que desenvolvedores incorporem recursos de pesquisa avançados em seus aplicativos e sites, melhorando a capacidade de descoberta e acesso a informações.
Alguns dos recursos oferecidos pelo Azure AI Search incluem:
Busca Avançada: Oferece recursos avançados de pesquisa, incluindo pesquisa de texto completo, pesquisa por relevância, suporte para sinônimos, pesquisa por facetas e sugestões de consulta.
Relevância Personalizada: Permite ajustar a relevância dos resultados da pesquisa com base nas preferências do usuário, histórico de navegação e outros fatores contextuais.
Busca Visual: Oferece a capacidade de realizar pesquisas baseadas em imagens, identificando objetos, marcas ou características visuais específicas.
Reconhecimento de Linguagem Natural: Suporta consultas de pesquisa em linguagem natural, permitindo que os usuários realizem pesquisas de forma mais intuitiva e conversacional.
Recuperação de Informações: Oferece recursos para indexar, armazenar e recuperar informações de maneira eficiente, mesmo em grandes volumes de dados não estruturados.
Gerenciamento de Conteúdo: Facilita o gerenciamento de conteúdo, permitindo a indexação e pesquisa em diferentes tipos de documentos e fontes de dados, como documentos do Microsoft Office, PDFs, bancos de dados e muito mais.
Esses recursos permitem que os desenvolvedores criem experiências de pesquisa poderosas e personalizadas em seus aplicativos e sites, melhorando a descoberta de informações e a experiência do usuário.



2º Passo: Criar um recurso de serviços de IA do Azure.
Os recursos de serviços de IA do Azure são componentes da plataforma de computação em nuvem Microsoft Azure que fornecem funcionalidades relacionadas à inteligência artificial (IA) para desenvolvedores e empresas. Esses recursos permitem que os usuários incorporem recursos de IA em seus aplicativos e processos de negócios, sem a necessidade de construir toda a infraestrutura do zero. Alguns exemplos de recursos de serviços de IA do Azure incluem:
Serviços Cognitivos: Oferece uma variedade de APIs pré-treinadas para análise de texto, reconhecimento de voz, visão computacional e outras tarefas de IA.
Azure Machine Learning: Uma plataforma completa de machine learning que permite aos usuários treinar, implantar e gerenciar modelos de machine learning em escala.
Azure Bot Services: Permite a criação e implantação de chatbots inteligentes usando tecnologias de processamento de linguagem natural (NLP) e aprendizado de máquina.
Azure Databricks: Uma plataforma de análise de big data que integra o Apache Spark com os serviços de nuvem do Azure, oferecendo recursos avançados de análise de dados e machine learning.
Azure Language Understanding (LUIS): Um serviço de compreensão de linguagem natural que permite criar aplicativos com interfaces de conversação de forma fácil e eficiente.
Azure Speech Services: Fornece capacidades avançadas de reconhecimento de fala, permitindo a conversão de áudio em texto e vice-versa, além de análise de sentimentos e identificação de idiomas.
Esses recursos de serviços de IA do Azure permitem que as empresas aproveitem as tecnologias de IA de ponta sem terem que construir toda a infraestrutura necessária internamente. Eles podem ser facilmente integrados em aplicativos existentes ou usados para criar soluções inteligentes e avançadas.

3º Passo: Criar uma conta de armazenamento.
Criar uma conta de armazenamento geralmente se refere ao processo de configurar uma conta em um serviço de armazenamento em nuvem, como Microsoft Azure, Amazon Web Services (AWS), Google Cloud Platform (GCP) ou outros provedores de serviços de nuvem. Essas contas de armazenamento são essenciais para armazenar dados de maneira segura, acessível e escalável na nuvem.
Aqui estão os passos gerais para criar uma conta de armazenamento em um serviço de nuvem:
Escolha do Provedor de Nuvem: Decida qual provedor de serviços de nuvem deseja usar com base em suas necessidades, requisitos de segurança, custos e outros fatores.
Acesse o Portal do Provedor de Nuvem: Faça login no portal do provedor de nuvem escolhido usando uma conta válida.

Navegue até a seção de Serviços de Armazenamento: Encontre a seção ou o serviço específico de armazenamento oferecido pelo provedor de nuvem. Geralmente, esses serviços são destacados no painel ou no menu principal do portal.
Inicie o Processo de Criação de Conta: Dentro da seção de armazenamento, procure por opções para criar uma conta de armazenamento. Essas opções podem variar de acordo com o provedor de nuvem, mas geralmente envolvem fornecer informações básicas, como nome da conta, região de data center, nível de redundância e configurações de segurança.
Configure as Opções de Segurança e Acesso: Durante o processo de criação da conta, você geralmente terá a opção de configurar medidas de segurança, como chaves de acesso, políticas de acesso, firewalls de rede e criptografia.
Revisão e Confirmação: Revise todas as configurações selecionadas e informações fornecidas para garantir que estejam corretas e atendam às suas necessidades. Depois de revisar, confirme a criação da conta.
Gerenciamento da Conta: Após a criação da conta, você terá acesso a um painel de controle onde poderá gerenciar sua conta de armazenamento. Isso inclui a criação e gerenciamento de contêineres, a configuração de permissões de acesso, a monitoração do uso e muito mais.
Uma vez criada, sua conta de armazenamento estará pronta para ser usada para armazenar uma variedade de dados, como arquivos, bancos de dados, imagens, vídeos e outros recursos, dependendo das capacidades oferecidas pelo provedor de nuvem escolhido.

4º Passo:  Carregar documentos no Armazenamento do Azure no Contêineres.
5º Passo: Indexar os documentos, importando os dados do Contêineres, Armazenamento de Blobs do Azure.
6º Passo: Consultar o Indice, use o Gerenciador de pesquisa para escrever e testar consultas. O explorador de pesquisa é uma ferramenta incorporada no portal do Azure oferecem uma maneira fácil de validar a qualidade do seu índice de pesquisa. Você pode usar o Gerenciador de pesquisa para escrever consultas e revisar resultados em JSON.

