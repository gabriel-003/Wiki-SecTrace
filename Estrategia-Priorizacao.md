---

# Estratégia de Priorização  

A ideia é priorizar tarefas que desbloqueiam outras áreas do projeto e garantir que funcionalidades essenciais estejam operacionais o mais cedo possível. As Fases de Desenvolvimento não estão em uma ordem necessariamente cronólogica. O foco da priorização em cada fase é na seção **Tarefas Prioritárias** de cada uma.

## **Fases de Desenvolvimento**  

### **Configuração da Infraestrutura** 
> *Objetivo: Estabelecer a base para o desenvolvimento e testes do projeto.*  

**Tarefas Prioritárias:**  
- Configuração da **instância EC2 na AWS** com os serviços necessários.  
- Instalação do ambiente de desenvolvimento com **Python + Flask**.  
- Configuração inicial do **SQLite** para persistência de dados.  
- Criação do repositório no **GitHub** e definição do fluxo de trabalho.  

---

### **Desenvolvimento do Backend**
> *Objetivo: Criar a API principal para manipulação de dados e regras de negócio.*  

**Tarefas Prioritárias:**  
- Estruturar o projeto Flask e definir as rotas principais.  
- Criar os modelos e a comunicação com o **SQLite**.  
- Implementar as funções essenciais para coleta e armazenamento dos dados.  
- Desenvolver testes básicos para garantir a estabilidade das operações.  

---

### Desenvolvimento do Frontend** 
> *Objetivo: Criar a interface de usuário para interação com o sistema.*  

**Tarefas Prioritárias:**  
- Definir a estrutura do **HTML, CSS e JavaScript**.  
- Criar as primeiras telas e componentes principais.  
- Implementar a comunicação com a API Flask via requisições **HTTP**.  
- Ajustar o design para garantir uma boa experiência do usuário.  

---

### **Fase 4 - Ajustes e Otimizações**  
> *Objetivo: Melhorar a performance, segurança e estabilidade do projeto antes da primeira versão pública.*  

**Tarefas Prioritárias:**  
- Revisão da segurança na API (autenticação, rate limiting, etc.).  
- Implementação de logs e monitoramento na instância EC2.  
- Testes de carga para avaliar a performance do SQLite e do Flask.  
- Documentação do código e guias de uso.  

---

# **Conclusão**  
Com essa estratégia de priorização, garantimos que o projeto **SecTrace** evolua de forma estruturada, sempre focando em entregar valor rapidamente e reduzir riscos técnicos.  

Caso o escopo mude ou novas demandas surjam, a equipe poderá revisar e adaptar as prioridades conforme necessário.
