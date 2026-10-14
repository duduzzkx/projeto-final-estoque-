# Nome do Sistema

> Substitua o título acima pelo nome do seu sistema e preencha cada seção deste documento.
> Este README é o **documento de visão** do projeto (entrega **AVA 1**) e, ao longo do curso,
> também será o manual técnico de como executar o sistema.

| | |
|---|---|
| **Aluno(a)** | Eduardo Massi |
| **Turma** |TEC-N-001788/2026 |
| **Opção escolhida** | Controle de Estoque |
| **Versão atual** | 0.1.0 |

---

## 1. Visão geral

### 1.1 Problema
<!-- Que problema o sistema resolve? Quem sofre com esse problema hoje e como ele é resolvido (planilha, papel, WhatsApp...)? 3 a 5 linhas. -->O sistema busca resolver o problema da desorganização no controle de estoque, que pode dificultar o acompanhamento dos produtos disponíveis. Atualmente, esse controle pode ser realizado de forma manual, por meio de anotações, planilhas ou outros métodos pouco centralizados. Isso pode causar erros na quantidade registrada, perda de informações e dificuldade para identificar produtos que precisam ser repostos. O sistema pretende centralizar e facilitar o gerenciamento dessas informações.

### 1.2 Canvas do projeto

| Bloco | Resposta |
|---|---|
| **Usuários** (quem usa o sistema) |Funcionários responsáveis pelo estoque e gestores do estabelecimento. |
| **Problema** (dor atual) | Desorganização no controle de produtos, dificuldade para saber as quantidades disponíveis e risco de falta ou excesso de estoque.|
| **Proposta de valor** (o que melhora com o sistema) |Centralizar o controle do estoque, facilitando o cadastro, a consulta e a atualização dos produtos e permitindo acompanhar melhor a situação do estoque. |
| **Funcionalidades principais** | 	Cadastrar, editar, excluir e consultar produtos; registrar entradas e saídas de produtos; controlar quantidades em estoque; pesquisar produtos; identificar produtos com estoque baixo.|
| **Informações que o sistema guarda** |	Produtos, código, nome, descrição, categoria, quantidade em estoque, estoque mínimo, preço e registros de entradas e saídas. |
| **Indicadores** (o que o gestor quer acompanhar) |	Quantidade total de produtos, produtos com estoque baixo, produtos sem estoque, entradas e saídas de produtos e valor estimado do estoque. |
| **Restrições** (prazo, tecnologia, equipe) | Projeto individual · Java 21 · Spring Boot 4 · entrega v1.0 em 11/11 |

---

## 2. Requisitos

### 2.1 Requisitos funcionais (o que o sistema FAZ)

| ID | Requisito | Nível |
|---|---|---|
| RF01 | Ex.: O sistema deve permitir cadastrar, listar, editar e excluir categorias. | Essencial |
| RF02 | | |
| RF03 | | |

### 2.2 Requisitos não funcionais (COMO o sistema deve ser)

| ID | Requisito |
|---|---|
| RNF01 | O sistema deve ser acessado pelo navegador (aplicação web). |
| RNF02 | O sistema deve exigir login e senha; as senhas devem ser armazenadas criptografadas. |
| RNF03 | |

### 2.3 Regras de negócio (as REGRAS do negócio que o sistema precisa respeitar)

| ID | Regra |
|---|---|
| RN01 | Ex.: Não é permitido registrar uma saída maior que o saldo do produto. |
| RN02 | |

---

## 3. Histórias de usuário

Formato: **Como** *[papel]*, **quero** *[ação]*, **para** *[benefício]*.

**HU01 —** Como ..., quero ..., para ...
- Critério de aceite: ...
- Critério de aceite: ...

**HU02 —** Como ..., quero ..., para ...
- Critério de aceite: ...

---

## 4. Modelo de dados

<!-- Encontro 2: apague este comentário (as duas linhas) e cole aqui o diagrama de classes
     em Mermaid (bloco que começa com ```mermaid), conforme o manual do Encontro 2. -->

---

## 5. Como executar

### No GitHub Codespaces (recomendado)
1. No repositório, clique em **Code → Codespaces → Create codespace on main** (ou abra o Codespace existente).
2. Aguarde a preparação do ambiente.
3. No terminal, execute:
   ```bash
   mvn spring-boot:run
   ```
4. Quando aparecer o aviso da porta **8080**, clique em **Abrir no navegador**.

### No computador (ferramentas instaladas)
Requisitos: JDK 21 e uma IDE (IntelliJ IDEA ou VS Code com o *Extension Pack for Java*).
Abra o projeto na IDE e execute a classe `SistemaApplication`. Acesse `http://localhost:8080`.

### Acesso
| Usuário | Senha | Perfil |
|---|---|---|
| admin | admin123 | Administrador |
| operador | operador123 | Operador |

*(o login passa a ser exigido a partir do Encontro 7)*

---

## 6. Tecnologias
Java 21 · Spring Boot 4 · Spring MVC · Thymeleaf · Bootstrap 5 · Spring Data JPA · H2 (desenvolvimento) · MySQL (produção) · Spring Security · Git/GitHub

## 7. Uso de inteligência artificial
<!-- Registre aqui, de forma resumida, quando e como você usou ferramentas de IA de forma relevante no projeto. -->

## 8. Histórico de versões
| Versão | Data | Descrição |
|---|---|---|
| 0.1.0 | | Projeto inicial criado a partir do repositório modelo |
