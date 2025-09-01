# README – Implementação de Serviços AWS

**Data:** 28/08/2025
**Empresa:** Stark Technologies
**Responsável:** Miguel Herrera

## 📖 Introdução

Este README documenta o processo de implementação de serviços AWS na **Stark Technologies**, conduzido por **Miguel Herrera**.
O objetivo principal foi modernizar a infraestrutura da empresa através da adoção de serviços em nuvem que proporcionam:

* Maior escalabilidade;
* Redução de custos operacionais;
* Melhor experiência de uso para clientes e colaboradores.

Foram escolhidos **três serviços principais da AWS**: **Amazon CloudFront**, **Amazon EC2 Auto Scaling** e **Amazon SQS**, cada um responsável por solucionar problemas estratégicos de desempenho, disponibilidade e eficiência.

---

## ⚙️ Descrição do Projeto

A implementação foi estruturada em três etapas, cada uma voltada para um serviço específico e seus respectivos casos de uso.

### Etapa 1: Amazon CloudFront

**Foco:** Rede de distribuição de conteúdo (CDN) que entrega dados com baixa latência.

**Caso de Uso:**
O site institucional e o portfólio de projetos da Stark Technologies passaram a ser distribuídos através do CloudFront. Dessa forma, arquivos estáticos como **imagens, PDFs e vídeos** são servidos a partir de **edge locations**, garantindo:

* Menor tempo de carregamento;
* Redução da carga nos servidores de origem;
* Melhor experiência para os usuários espalhados globalmente.

---

### Etapa 2: Amazon EC2 Auto Scaling

**Foco:** Ajuste automático da quantidade de instâncias EC2 de acordo com a demanda.

**Caso de Uso:**
O sistema de gestão interna (ERP) da empresa foi migrado para instâncias EC2. Foi configurado um grupo de **Auto Scaling** que cria ou encerra instâncias conforme regras definidas, como o uso de CPU maior que 65%.

Benefícios alcançados:

* Custos otimizados (sem máquinas ociosas);
* Alta disponibilidade;
* Ambiente flexível para horários de pico e baixa demanda.

---

### Etapa 3: Amazon SQS

**Foco:** Serviço de filas para processamento assíncrono de mensagens.

**Caso de Uso:**
No fluxo de vendas, tarefas como envio de notificações, atualização de relatórios e integrações externas foram desacopladas utilizando o **Amazon SQS**. Mensagens ficam enfileiradas e são processadas em segundo plano por consumidores executados em **AWS Lambda**.

Resultados obtidos:

* Redução do tempo de resposta do sistema principal;
* Processamento confiável, sem perda de mensagens;
* Escalabilidade automática baseada na quantidade de itens na fila.

---

## ✅ Conclusão

A adoção desses três serviços trouxe ganhos significativos para a Stark Technologies:

* **Performance:** O site ficou mais rápido e responsivo;
* **Eficiência:** A infraestrutura ajusta-se automaticamente à carga;
* **Escalabilidade:** Processos assíncronos eliminam gargalos e aumentam a confiabilidade.

Esse projeto é o **primeiro passo rumo à transformação digital da empresa**, e recomenda-se a expansão do uso da AWS em outras frentes, como **Amazon RDS** e **Amazon Lambda** para novas aplicações.

---

## 📎 Documentação Anexa

* Guia de configuração do **Amazon CloudFront**;
* Políticas de escalonamento utilizadas no **EC2 Auto Scaling**;
* Fluxograma de mensagens no **Amazon SQS**.

---

**Assinatura do Responsável pelo Projeto:**
Miguel Herrera

---

👉 Esse modelo você pode reaproveitar em qualquer entrega de projeto AWS, só trocando os serviços e os casos de uso.

Quer que eu monte uma **versão em Markdown bem estilizada** (com ícones, checklists e blocos de código) para já ficar pronta pra GitHub?
