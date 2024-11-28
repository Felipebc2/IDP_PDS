# **Projeto de Criação do Aplicativo - Impress Express**

## **1. Diagnóstico e Teorização**

**Quem Somos:**  
Impress Express é uma startup que visa democratizar a impressão 3D, oferecendo soluções práticas e acessíveis. Nosso objetivo é facilitar o acesso à tecnologia e estimular a criatividade.

**Partes Envolvidas:**  
- **Contratante:** Impress Express.  
- **Parceiros:** AWS (armazenamento), Stripe (pagamentos).  
- **Equipe:** 3 fundadores e desenvolvedores, além de futuros colaboradores.  

**Público-Alvo:**  
Nosso público-alvo inclui:  
- Entusiastas de tecnologia e design.  
- Empresas interessadas em prototipagem.  
- Estudantes e educadores.  
Perfil predominante: 18-45 anos, escolaridade média a alta, com interesse por inovação tecnológica.

---

## **2. Levantamento de Requisitos**

### **Requisitos Funcionais**
1. Catálogo de produtos 3D com preços, descrições, materiais e avaliações.
2. Upload de modelos 3D (formatos STL, OBJ, G-code).
3. Cálculo automático do preço com base em material, tamanho e complexidade.
4. Sistema de compras com integração de pagamento e rastreamento.
5. Login e cadastro seguro.

### **Requisitos Não Funcionais**
- **Performance:** Carregamento de telas em até 3 segundos.  
- **Compatibilidade:** Suporte a Android e iOS (versões recentes).  
- **Segurança:** Criptografia SSL e autenticação OAuth 2.0.  
- **Escalabilidade:** Suportar até 10.000 usuários simultâneos.  

### **Regras de Negócio**
1. Somente arquivos STL, OBJ e G-code serão aceitos.
2. O preço considera o volume, material e complexidade.
3. Definir prazo de entrega com base na localização e demanda.

### **Técnicas Utilizadas**
- **Entrevistas:** Perguntas feitas aos stakeholders:
  - Qual a principal funcionalidade esperada?
  - Quais problemas o app deve resolver?  
- **Workshops:** Sessões para identificar fluxos de navegação e validar requisitos.

---

## **3. Prototipação do App**

Prototipação das principais telas usando Figma ou Canva, incluindo:  
- Tela inicial com o catálogo de produtos.  
- Tela de upload para modelos 3D.  
- Carrinho de compras e página de rastreamento.

---

## **4. Planejamento**

### **Escopo**
Funcionalidades detalhadas incluem:  
- Visualização de catálogo.  
- Upload e análise automática de modelos.  
- Rastreamento de pedidos.

### **Cronograma**
- **Semana 1-3:** Levantamento de requisitos e prototipação.  
- **Semana 4-16:** Desenvolvimento do backend e frontend.  
- **Semana 17-20:** Testes e ajustes finais.  
- **Semana 21:** Lançamento Beta.
- **Tempo Total:** Aproximadamente 5 meses (Com Margem de Erro de 5%)

### **Riscos e Mitigação**
- **Atrasos no desenvolvimento:** Planejamento de contingência.  
- **Mudanças nos requisitos:** Reuniões semanais com stakeholders.  

### **Plano de Comunicação**
- Reuniões semanais via Google Meet.  
- Relatórios diários no Slack.

---

## **5. Arquitetura de Software**

### **Tecnologias Selecionadas**
- **Frontend:** React Native.  
- **Backend:** Node.js com Express.js.  
- **Banco de Dados:** MongoDB.

### **Arquitetura**
- Microservices para modularidade.  

### **Integrações**
- Stripe para pagamentos.  
- AWS S3 para armazenamento.

---

## **6. Estrutura Analítica do Projeto (EAP)**

<a href="https://ibb.co/fp2bcYc"><img src="https://i.ibb.co/bBPxfgf/EAP.png" alt="EAP" border="0"></a>

---

## **7. Testes**

### **Objetivo**
Garantir a funcionalidade e desempenho esperados.

### **Tipos de Testes**
- **Funcionais:** Validação de todas as funcionalidades principais.  
- **Não Funcionais:** Avaliação de desempenho e escalabilidade.  
- **Usabilidade:** Testes com usuários reais para validar a interface.

---

## **8. Garantia de Qualidade**

### **Atividades**
- Implementar práticas de DevOps (CI/CD).  
- Auditorias de qualidade periódicas.  
- Monitorar métricas como cobertura de testes e bugs encontrados.

---

## **9. Documentação**

Manter a documentação atualizada no **ClickUp** ou similar, incluindo:  
- Requisitos levantados.  
- Resultados dos testes.  
- Feedback do Beta.

---

## **Conclusão**

Este aplicativo visa aumentar a visibilidade da Impress Express no mercado, oferecendo uma solução robusta e fácil de usar. Ele combina tecnologia avançada com foco na experiência do cliente, tornando a impressão 3D mais acessível e prática.

---
