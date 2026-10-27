
# WBM Gerador de Currículos ATS

**Uma ferramenta para criação, aprimoramento e análise de currículos com foco em compatibilidade com sistemas ATS (Applicant Tracking Systems).**

🌐 **Acesse o site:** [https://6ad6bd739494a.site123.me/](https://6ad6bd739494a.site123.me/)

---

## 📌 Sobre o projeto

O **WBM Gerador de Currículos ATS** é uma aplicação desenvolvida para auxiliar candidatos na preparação de currículos mais organizados, profissionais e alinhados aos requisitos de vagas de emprego.

A ferramenta permite importar ou inserir o conteúdo de um currículo, analisar sua compatibilidade com uma descrição de vaga, identificar palavras-chave relevantes e gerar uma versão aprimorada para revisão do usuário.

O projeto busca tornar o processo de preparação de currículos mais acessível, prático e intuitivo, especialmente para pessoas que desejam melhorar sua apresentação profissional e aumentar a aderência de seus currículos aos requisitos divulgados pelas empresas.

O aplicativo está disponível publicamente por meio da plataforma SITE123.

## 🎯 Objetivos

- Facilitar a preparação e a organização de currículos profissionais.
- Auxiliar na análise de compatibilidade entre currículo e vaga.
- Identificar palavras-chave presentes e ausentes em relação aos requisitos da oportunidade.
- Apoiar a elaboração de um currículo aprimorado sem inventar experiências ou qualificações.
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

### 3. Currículo aprimorado

A aplicação oferece recursos para gerar uma versão aprimorada do currículo, priorizando clareza, organização e adequação textual.

O conteúdo gerado deve ser revisado pelo usuário antes de ser utilizado em candidaturas.

**Princípio fundamental:** o aprimoramento não deve inventar experiências profissionais, competências, resultados, certificações ou conquistas que não tenham sido informados pelo candidato.

### 4. Palavras-chave e requisitos da vaga

A ferramenta auxilia na identificação de termos relevantes para a oportunidade, permitindo ao usuário avaliar quais informações precisam ser incluídas ou melhor esclarecidas.

A identificação de um requisito ausente não significa que o candidato possua aquela competência. Cabe ao usuário confirmar sua experiência antes de acrescentar qualquer informação ao currículo.

### 5. Resultados quantificados

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

### 6. Edição e pré-visualização

O usuário pode revisar e editar o conteúdo do currículo aprimorado antes de exportá-lo.

A pré-visualização auxilia na conferência das informações, da organização das seções e da apresentação geral do documento.

É recomendável conferir cuidadosamente o cabeçalho, os contatos e as informações extraídas de arquivos importados.

### 7. Exportação para PDF

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

A aplicação utiliza recursos executados no navegador para realizar as principais operações do gerador, incluindo importação de documentos, edição, análise de compatibilidade, geração do currículo aprimorado e exportação para PDF.

Conforme o diagnóstico realizado durante o desenvolvimento, as funcionalidades principais operam localmente no navegador, sem backend ou banco de dados externo conectado ao gerador.

A autenticação e o armazenamento de informações disponibilizados pela plataforma devem ser considerados separadamente das funcionalidades locais do aplicativo.

## 👤 Acesso e dados por usuário

O site possui acesso público por meio do endereço oficial informado neste documento.

Foi realizado um teste de acesso utilizando a conta pessoal de outra pessoa, e o comportamento observado foi satisfatório, incluindo a preservação da memória por usuário.

Essa observação corresponde ao teste realizado e não representa uma auditoria completa de segurança ou de isolamento de dados.

O acesso público ao site não significa, por si só, que todas as páginas estejam protegidas por autenticação. A exigência de login para utilizar o gerador depende da configuração efetiva da plataforma.

No estado atual do projeto, não se declara como implementada uma obrigatoriedade de login para acessar o gerador.

## 🔒 Privacidade e boas práticas

O usuário deve revisar as informações inseridas e evitar compartilhar dados pessoais desnecessários.

Recomendações:

- Utilize somente informações profissionais verdadeiras.
- Confira o conteúdo extraído de documentos antes de gerar a versão final.
- Não inclua informações pessoais que não sejam necessárias para a candidatura.
- Revise os dados de contato antes de exportar o currículo.
- Não interprete a pontuação ATS como garantia de contratação.
- Mantenha uma cópia do currículo original para comparação e conferência.

A privacidade e a persistência dos dados também dependem do funcionamento da plataforma de hospedagem, das configurações de acesso e dos recursos utilizados pelo navegador.

## ⚠️ Limitações conhecidas

- A extração de texto depende dos recursos utilizados para processar DOCX e PDF.
- PDFs digitalizados, compostos somente por imagens, podem exigir reconhecimento óptico de caracteres (OCR).
- A análise ATS é uma estimativa e pode não reproduzir os critérios de todos os sistemas de recrutamento.
- A compatibilidade depende da qualidade do texto fornecido e da descrição da vaga.
- Informações extraídas automaticamente podem exigir correção manual.
- Resultados quantificados devem ser preenchidos com dados reais e verificáveis.
- O formato final do PDF deve ser conferido antes do envio a recrutadores.

## 🚀 Como utilizar

1. Acesse o site: [https://6ad6bd739494a.site123.me/](https://6ad6bd739494a.site123.me/)
2. Abra o gerador de currículos.
3. Importe um currículo compatível ou insira o texto manualmente.
4. Informe a descrição da vaga desejada.
5. Execute a análise de compatibilidade.
6. Revise as palavras-chave e os requisitos identificados.
7. Gere ou edite a versão aprimorada do currículo.
8. Preencha os resultados profissionais, quando aplicável, utilizando informações verdadeiras.
9. Confira a pré-visualização.
10. Exporte o currículo para PDF e revise o arquivo final.

## 🛠️ Desenvolvimento e manutenção

O WBM Gerador de Currículos ATS é um projeto em evolução. Melhorias futuras podem incluir aperfeiçoamentos na extração de documentos, na apresentação dos currículos, na análise de compatibilidade e na experiência de uso.

Alterações devem preservar as funcionalidades existentes, priorizar a segurança das informações e evitar custos desnecessários.

O projeto é desenvolvido com foco em acessibilidade, praticidade e utilidade para candidatos que desejam organizar melhor suas informações profissionais.

## 📄 Licença e direitos autorais

Este README documenta o projeto e suas funcionalidades conforme as informações disponíveis no momento de sua elaboração.

A publicação deste documento no GitHub não concede automaticamente licença para copiar, redistribuir, comercializar ou modificar o aplicativo. A utilização do código e dos demais materiais deve respeitar os direitos de seus respectivos titulares e a licença que vier a ser definida no repositório.

---

**Criador:** Washington Brito Miguel\
**Em:** Outubro de 2026\
**Direitos Reservados © 2026 — Washington Brito Miguel. Todos os direitos reservados.**

