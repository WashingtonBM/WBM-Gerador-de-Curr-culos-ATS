# WBM Gerador de Currículos ATS

**Uma ferramenta inteligente para criação, aprimoramento, transformação e análise de currículos com foco em compatibilidade com sistemas ATS (Applicant Tracking Systems).**

🌐 **Acesse o site:** [https://6ad6bd739494a.site123.me/](https://6ad6bd739494a.site123.me/)

---

## 📌 Sobre o projeto

O **WBM Gerador de Currículos ATS** é uma aplicação desenvolvida para auxiliar candidatos na preparação de currículos mais organizados, profissionais e alinhados aos requisitos de vagas de emprego.

A ferramenta permite importar ou inserir o conteúdo de um currículo, analisar sua compatibilidade com uma descrição de vaga, identificar palavras-chave relevantes e gerar uma versão aprimorada para revisão do usuário.

O projeto conta também com o **Agente WBM Criador e Transformador de Currículos ATS**, desenvolvido para automatizar a análise de uma oportunidade profissional e a transformação do currículo original em uma versão direcionada à vaga.

O agente utiliza inteligência artificial nativa da plataforma para analisar o currículo e a descrição da oportunidade em uma única chamada, produzir uma versão otimizada e apresentar um relatório estruturado de compatibilidade.

O projeto busca tornar o processo de preparação de currículos mais acessível, prático e intuitivo, especialmente para pessoas que desejam melhorar sua apresentação profissional e aumentar a aderência de seus currículos aos requisitos divulgados pelas empresas.

O aplicativo está disponível publicamente por meio da plataforma SITE123.

## 🎯 Objetivos

- Facilitar a preparação e a organização de currículos profissionais.
- Auxiliar na análise de compatibilidade entre currículo e vaga.
- Identificar palavras-chave presentes e ausentes em relação aos requisitos da oportunidade.
- Oferecer um agente inteligente para criação e transformação de currículos direcionados a vagas específicas.
- Automatizar a identificação de requisitos atendidos, parcialmente atendidos e não identificados.
- Apoiar a elaboração de currículos aprimorados sem inventar experiências ou qualificações.
- Apresentar uma estimativa de compatibilidade entre o currículo e a oportunidade.
- Permitir que o candidato revise e edite o conteúdo antes de utilizá-lo.
- Simplificar a exportação do currículo para PDF.
- Oferecer uma ferramenta acessível diretamente pelo navegador.

## ✨ Funcionalidades

### 1. Importação e entrada de currículos

A aplicação permite trabalhar com conteúdo de currículos por meio de entrada de texto e importação de arquivos compatíveis, incluindo:

- Arquivos DOCX.
- Arquivos PDF com texto extraível.
- Texto inserido ou colado diretamente no editor.

A extração depende dos recursos utilizados pelo aplicativo. PDFs digitalizados que contenham somente imagens podem não fornecer texto automaticamente.

### 2. Análise de compatibilidade ATS

O usuário pode inserir a descrição da vaga desejada e analisar a correspondência entre os requisitos da oportunidade e o conteúdo do currículo.

A análise auxilia na identificação de:

- Palavras-chave correspondentes.
- Termos relevantes que podem estar ausentes.
- Requisitos que merecem revisão.
- Oportunidades de melhoria na apresentação das informações profissionais.

A pontuação apresentada é uma estimativa de compatibilidade segundo os critérios implementados no aplicativo. Ela não representa uma nota oficial de um sistema de recrutamento nem garante aprovação em processos seletivos.

### 3. Agente WBM Criador e Transformador de Currículos ATS

O **Agente WBM** é uma funcionalidade de inteligência artificial integrada ao aplicativo, desenvolvida para criar e transformar currículos de acordo com os requisitos de uma vaga específica.

Seu funcionamento é automatizado e não utiliza formato de conversa ou chatbot.

O usuário fornece o currículo original e a descrição da vaga, podendo utilizar arquivos PDF ou DOCX nos dois campos, ou inserir as informações conforme os recursos disponíveis.

Após preencher os dados, basta clicar no botão:

**GERAR CURRÍCULO OTIMIZADO PARA ESTA VAGA**

O agente realiza uma única chamada de IA para executar as seguintes tarefas:

- Interpretar a descrição da vaga.
- Identificar requisitos obrigatórios e desejáveis.
- Identificar palavras-chave e competências relevantes.
- Comparar os requisitos com as informações do currículo original.
- Identificar experiências e qualificações comprovadas.
- Reorganizar e reescrever o currículo com linguagem profissional, objetiva e adequada a sistemas ATS.
- Produzir um relatório estruturado de compatibilidade.
- Apresentar sugestões de melhoria que dependam de confirmação do candidato.

O resultado da transformação é encaminhado automaticamente ao editor de currículos existente, permitindo revisão, edição, pré-visualização e exportação para PDF.

### 4. Relatório de compatibilidade do agente

Após a execução, o agente apresenta um relatório com:

- **Compatibilidade estimada:** percentual de correspondência entre o currículo e os requisitos da vaga.
- **Requisitos atendidos:** requisitos identificados e sustentados pelas informações do currículo.
- **Requisitos parcialmente atendidos:** requisitos que apresentam correspondência incompleta ou que precisam de esclarecimento.
- **Requisitos não identificados:** requisitos que não foram encontrados no currículo original.
- **Palavras-chave encontradas:** termos relevantes presentes no conteúdo profissional.
- **Palavras-chave ausentes:** termos da vaga que não foram identificados no currículo.
- **Sugestões de melhoria:** recomendações para aprimorar a apresentação das qualificações e experiências verdadeiras do candidato.

A compatibilidade estimada pelo agente é uma avaliação produzida pela inteligência artificial. Ela deve ser interpretada como uma referência de adequação à vaga, e não como garantia de aprovação em sistemas ATS ou processos seletivos.

### 5. Integração com a análise ATS local

O agente trabalha em conjunto com o mecanismo de análise ATS já existente no aplicativo.

Após a transformação:

- O currículo otimizado é inserido no editor existente.
- A análise ATS local é executada sobre o novo conteúdo.
- A pontuação ATS é recalculada.
- Os resultados da análise local são apresentados separadamente da avaliação de compatibilidade produzida pela IA.

Essa separação permite ao candidato consultar duas avaliações diferentes:

1. A compatibilidade estimada pelo agente em relação aos requisitos da vaga.
2. A pontuação calculada pelo mecanismo ATS local do aplicativo.

As duas avaliações utilizam critérios distintos e não devem ser interpretadas como métricas equivalentes.

### 6. Controle de consumo de IA

O Agente WBM foi planejado para utilizar uma arquitetura econômica, concentrando as tarefas de análise e transformação em uma única chamada de inteligência artificial por execução.

As regras de funcionamento incluem:

- A IA é acionada somente após o clique explícito do usuário.
- Não existem chamadas automáticas em segundo plano.
- Não há conversa interativa com o agente.
- Não são realizadas chamadas adicionais para gerar pontuações ou revisar o resultado.
- O botão de execução deve impedir acionamentos repetidos durante o processamento.
- Erros não devem provocar novas chamadas automáticas.
- Uma nova tentativa depende de ação explícita do usuário.

O agente utiliza os créditos de IA disponibilizados pela própria plataforma, conforme os limites da conta.

O consumo depende do volume de informações enviado, incluindo o tamanho do currículo e da descrição da vaga. Não há um valor fixo oficial de créditos por chamada documentado neste projeto.

A disponibilidade contínua depende da cota de créditos incluída no plano da plataforma.

### 7. Princípio de veracidade das informações

A integridade das informações profissionais é um princípio fundamental do projeto.

O agente não deve inventar ou atribuir ao candidato:

- Experiências profissionais não informadas.
- Empresas, cargos ou períodos de trabalho fictícios.
- Cursos e certificações inexistentes.
- Competências não comprovadas.
- Resultados ou indicadores sem confirmação.
- Números, percentuais ou conquistas não fornecidos pelo candidato.

A identificação de um requisito ausente não significa que o candidato possua aquela competência.

O agente deve apontar lacunas e sugerir melhorias, mas cabe ao usuário confirmar qualquer informação antes de acrescentá-la ao currículo.

A meta de alcançar 95% a 100% de compatibilidade é um objetivo de otimização, não uma promessa de resultado. A pontuação depende da vaga, do histórico profissional e dos requisitos efetivamente comprovados.

### 8. Currículo aprimorado

Além do agente, a aplicação oferece recursos para gerar uma versão aprimorada do currículo, priorizando clareza, organização e adequação textual.

O conteúdo gerado deve ser revisado pelo usuário antes de ser utilizado em candidaturas.

**Princípio fundamental:** o aprimoramento não deve inventar experiências profissionais, competências, resultados, certificações ou conquistas que não tenham sido informados pelo candidato.

### 9. Palavras-chave e requisitos da vaga

A ferramenta auxilia na identificação de termos relevantes para a oportunidade, permitindo ao usuário avaliar quais informações precisam ser incluídas ou melhor esclarecidas.

A identificação de um requisito ausente não significa que o candidato possua aquela competência. Cabe ao usuário confirmar sua experiência antes de acrescentar qualquer informação ao currículo.

### 10. Resultados quantificados

A seção de resultados quantificados permite registrar realizações profissionais que possam demonstrar entregas, responsabilidades e resultados.

A funcionalidade oferece modelos de preenchimento relacionados a atividades como:

- Quantidade de atendimentos realizados.
- Volume de documentos processados.
- Cumprimento de metas.
- Redução de erros e retrabalho.
- Economia de tempo.
- Valores administrados.
- Melhorias em processos.

Os modelos utilizam marcadores para preenchimento e validação pelo usuário. Nenhum número, percentual ou resultado deve ser apresentado como verdadeiro sem confirmação.

O preenchimento da seção é opcional.

### 11. Edição e pré-visualização

O usuário pode revisar e editar o conteúdo do currículo aprimorado antes de exportá-lo.

O currículo transformado pelo Agente WBM também é encaminhado ao editor existente.

A pré-visualização auxilia na conferência das informações, da organização das seções e da apresentação geral do documento.

É recomendável conferir cuidadosamente o cabeçalho, os contatos e as informações extraídas de arquivos importados.

### 12. Exportação para PDF

O aplicativo oferece exportação do currículo para PDF, permitindo que o candidato salve o documento e o utilize em processos seletivos.

Antes de enviar o arquivo a uma empresa, recomenda-se verificar:

- Nome e informações de contato.
- Formação acadêmica.
- Experiências profissionais.
- Competências e resultados informados.
- Formatação e quebras de página.
- Ausência de marcadores de preenchimento não resolvidos.

## 🖥️ Plataforma e arquitetura

O projeto é desenvolvido e disponibilizado por meio do **SITE123 AI App Builder**.

A aplicação utiliza recursos executados no navegador para realizar as principais operações do gerador, incluindo:

- Importação de documentos.
- Extração de texto de PDF e DOCX.
- Edição e organização do currículo.
- Análise de compatibilidade ATS local.
- Pré-visualização.
- Exportação para PDF.

O Agente WBM utiliza o recurso nativo de IA de texto da plataforma, acionado durante o uso normal do aplicativo.

Sua arquitetura concentra a análise da vaga, a comparação com o currículo, a reescrita e a produção do relatório em uma única chamada de IA por execução.

O processamento posterior, incluindo a atualização da pontuação ATS local e a utilização do editor e da exportação PDF, aproveita os recursos existentes.

Conforme o diagnóstico realizado durante o desenvolvimento, as funcionalidades principais do gerador operam localmente no navegador, sem backend ou banco de dados externo conectado ao gerador.

A utilização da IA nativa da plataforma constitui uma integração específica para a geração de texto durante o uso do aplicativo.

A autenticação e o armazenamento de informações disponibilizados pela plataforma devem ser considerados separadamente das funcionalidades locais do aplicativo.

## 👤 Acesso e dados por usuário

O site possui acesso público por meio do endereço oficial informado neste documento.

Foi realizado um teste de acesso utilizando a conta pessoal de outra pessoa, e o comportamento observado foi satisfatório, incluindo a preservação da memória por usuário.

Essa observação corresponde ao teste realizado e não representa uma auditoria completa de segurança ou de isolamento de dados.

O acesso público ao site não significa, por si só, que todas as páginas estejam protegidas por autenticação. A exigência de login para utilizar o gerador depende da configuração efetiva da plataforma.

No estado atual do projeto, não se declara como implementada uma obrigatoriedade de login para acessar o gerador.

O aplicativo não possui, nesta versão, um sistema próprio de histórico persistente de currículos ou armazenamento externo dedicado para guardar todas as transformações realizadas.

## 🔒 Privacidade e boas práticas

O usuário deve revisar as informações inseridas e evitar compartilhar dados pessoais desnecessários.

Recomendações:

- Utilize somente informações profissionais verdadeiras.
- Confira o conteúdo extraído de documentos antes de gerar a versão final.
- Não inclua informações pessoais que não sejam necessárias para a candidatura.
- Revise os dados de contato antes de exportar o currículo.
- Não interprete a pontuação ATS como garantia de contratação.
- Mantenha uma cópia do currículo original para comparação e conferência.
- Confira as informações produzidas pela IA antes de utilizá-las em candidaturas.

A privacidade e a persistência dos dados também dependem do funcionamento da plataforma de hospedagem, das configurações de acesso e dos recursos utilizados pelo navegador.

## ⚠️ Limitações conhecidas

- A extração de texto depende dos recursos utilizados para processar DOCX e PDF.
- PDFs digitalizados, compostos somente por imagens, podem exigir reconhecimento óptico de caracteres (OCR).
- A análise ATS local é uma estimativa e pode não reproduzir os critérios de todos os sistemas de recrutamento.
- A avaliação de compatibilidade produzida pela IA também é estimativa e pode apresentar variações.
- A compatibilidade depende da qualidade do texto fornecido e da descrição da vaga.
- Informações extraídas automaticamente podem exigir correção manual.
- A inteligência artificial pode apresentar erros de interpretação ou formatação, sendo necessária a revisão do resultado.
- A execução do agente depende da disponibilidade e da cota de créditos de IA da conta na plataforma.
- O consumo de créditos varia conforme o volume de informações enviado.
- Não há garantia de compatibilidade de 95% a 100% para todas as vagas.
- Resultados quantificados devem ser preenchidos com dados reais e verificáveis.
- O formato final do PDF deve ser conferido antes do envio a recrutadores.
- O aplicativo não garante entrevistas, aprovação em processos seletivos ou contratação.

## 🚀 Como utilizar

### Fluxo tradicional do gerador

1. Acesse o site: [https://6ad6bd739494a.site123.me/](https://6ad6bd739494a.site123.me/).
2. Abra o gerador de currículos.
3. Importe um currículo compatível ou insira o texto manualmente.
4. Informe a descrição da vaga desejada.
5. Execute a análise de compatibilidade.
6. Revise as palavras-chave e os requisitos identificados.
7. Gere ou edite a versão aprimorada do currículo.
8. Preencha os resultados profissionais, quando aplicável, utilizando informações verdadeiras.
9. Confira a pré-visualização.
10. Exporte o currículo para PDF e revise o arquivo final.

### Fluxo com o Agente WBM

1. Acesse o site: [https://6ad6bd739494a.site123.me/](https://6ad6bd739494a.site123.me/).
2. Abra a área **Agente WBM Criador e Transformador de Currículos ATS**.
3. Insira ou importe a descrição da vaga de emprego.
4. Insira ou importe o currículo original.
5. Confira os documentos e os dados fornecidos.
6. Clique em **GERAR CURRÍCULO OTIMIZADO PARA ESTA VAGA**.
7. Aguarde o processamento da inteligência artificial.
8. Consulte o relatório de compatibilidade, incluindo requisitos atendidos, parcialmente atendidos e não identificados.
9. Confira as palavras-chave encontradas e ausentes e as sugestões de melhoria.
10. Analise a pontuação estimada de compatibilidade apresentada pelo agente.
11. Consulte separadamente a pontuação ATS local recalculada pelo aplicativo.
12. Revise e edite o currículo transformado no editor existente.
13. Confira a pré-visualização.
14. Exporte o currículo para PDF.
15. Revise o arquivo final antes de enviá-lo à empresa.

**Importante:** cada execução do Agente WBM utiliza uma chamada de IA, acionada exclusivamente pelo usuário. Portanto, recomenda-se conferir os documentos antes de iniciar a transformação, evitando execuções desnecessárias e consumo adicional de créditos.

## 🛠️ Desenvolvimento e manutenção

O WBM Gerador de Currículos ATS é um projeto em evolução.

Sua arquitetura prioriza o reaproveitamento das funcionalidades existentes e a integração de novos recursos sem reconstruções desnecessárias.

Melhorias futuras podem incluir aperfeiçoamentos na extração de documentos, na apresentação dos currículos, na análise de compatibilidade e na experiência de uso.

Alterações devem:

- Preservar as funcionalidades existentes.
- Priorizar a segurança das informações.
- Evitar custos desnecessários.
- Aproveitar os recursos já disponíveis na plataforma.
- Evitar chamadas desnecessárias de inteligência artificial.
- Manter a integridade das informações profissionais.
- Não realizar publicação ou upgrade sem autorização explícita.

O projeto é desenvolvido com foco em acessibilidade, praticidade e utilidade para candidatos que desejam organizar melhor suas informações profissionais.

## 📄 Licença e direitos autorais

Este README documenta o projeto e suas funcionalidades conforme as informações disponíveis no momento de sua elaboração.

A publicação deste documento no GitHub não concede automaticamente licença para copiar, redistribuir, comercializar ou modificar o aplicativo. A utilização do código e dos demais materiais deve respeitar os direitos de seus respectivos titulares e a licença que vier a ser definida no repositório.

---

**Criador:** Washington Brito Miguel  
**Em:** Outubro de 2026  
**Direitos Reservados © 2026 — Washington Brito Miguel. Todos os direitos reservados.
