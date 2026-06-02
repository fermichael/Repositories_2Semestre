# Sistema de Cadastro de Notas e Frequência Escolar 🏫

Este é um script em Python simples e interativo projetado para ajudar no gerenciamento de notas e frequência de estudantes. O sistema valida as disciplinas permitidas pela escola, calcula a média aritmética de quatro notas, registra a frequência e gera um relatório final de aprovação ou reprovação.

---

## 🚀 Funcionalidades

* **Validação de Disciplinas:** Aceita apenas as matérias cadastradas no sistema, tratando automaticamente caracteres especiais e letras maiúsculas/minúsculas.
* **Cálculo de Média:** Solicita 4 notas (com validação para aceitar apenas valores de 0 a 10) e calcula a média final.
* **Controle de Frequência:** Registra a assiduidade do aluno na disciplina.
* **Status de Aprovação em Tempo Real:** Informa imediatamente se o aluno passou ou foi reprovado na matéria atual.
* **Relatório Final Completo:** Exibe um resumo de todas as disciplinas cursadas, médias, frequências e o status final antes de encerrar o programa.

---

## 📊 Regras de Negócio

### 1. Matérias Permitidas
O sistema está configurado exclusivamente para as seguintes disciplinas:
* Matemática
* História
* Física
* Educação Física

### 2. Critérios de Aprovação
Para ser considerado **Aprovado** em uma disciplina, o aluno precisa cumprir **ambos** os requisitos:
* **Média final** igual ou superior a **6.0**.
* **Frequência** igual ou superior a **50**.

---

## 🛠️ Como Executar o Projeto

### Pré-requisitos
* Ter o **Python 3.x** instalado em sua máquina.

### Passo a Passo

1. **Clonar ou baixar o arquivo:**
   Crie um arquivo chamado `main.py` (ou o nome de sua preferência) e cole o código do sistema.

2. **Abrir o terminal:**
   Navegue até a pasta onde o arquivo foi salvo.

3. **Executar o comando:**
   ```bash
   python main.py
