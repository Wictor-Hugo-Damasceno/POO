# Atividade Prática – Controle de Versões com Git e GitHub

Este documento apresenta a documentação e a comprovação das etapas realizadas durante a atividade prática de controle de versões utilizando Git, GitHub e o terminal integrado do Visual Studio Code (VS Code).

---

## 1. Descrição das Etapas e Comandos Utilizados

### Etapa 1: Criação do Repositório no GitHub
* **Descrição**: Foi criado um repositório público chamado `POO` diretamente na plataforma do GitHub, já contendo a inicialização do ficheiro de documentação e o registo do commit inicial.

### Etapa 2: Clonagem do Repositório (`git clone`)
* **Descrição**: O repositório remoto foi clonado para o ambiente de trabalho local utilizando o terminal integrado do VS Code.
* **Comando Utilizado**:
  ```bash
  git clone [https://github.com/Wictor-Hugo-Damasceno/POO.git](https://github.com/Wictor-Hugo-Damasceno/POO.git)
  cd POO
<img width="812" height="127" alt="image" src="https://github.com/user-attachments/assets/8b1896c7-c9d3-4495-a9a1-7828b79ee0e7" />

### Etapa 3: Edição e Versionamento
git add .
git commit -m "Classe teste"
git pull origin main --rebase
git push origin main

### Etapa 4: Criação e Alteração de Ramo / Branch (`git checkout`, `git add`, `git commit`, `git push`)
* **Descrição**: Foi criado e alternado para um novo ramo chamado `novo-ramo` utilizando o comando `git checkout -b novo-ramo` no terminal integrado do VS Code. Em seguida, as alterações foram preparadas com `git add .`, registadas no histórico local com o commit `"Comproção de ramo"` e enviadas com sucesso para o repositório remoto no GitHub através do comando `git push origin novo-ramo`.
* **Comandos Utilizados**:
  ```bash
  git checkout -b novo-ramo
  git add .
  git commit -m "Comproção de ramo"
  git push origin novo-ramo
  
  <img width="699" height="242" alt="image" src="https://github.com/user-attachments/assets/d9860d65-23d1-4127-8279-706251e95724" />
