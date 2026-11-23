# img-Py-MFI

![Licença](https://img.shields.io/badge/licenca-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow.svg)

Aplicação desenvolvida para processamento, análise visual e **dosagem de MFI** (Mean Fluorescence Intensity / Intensidade Média de Fluorescência) a partir de imagens e medidas-resumo. 

Projeto mantido pelo **Laboratório de Análise de Dados**.

---

## 📌 Sobre o Projeto

O **`img-PEP-MFI`** tem como objetivo automatizar o cálculo e a avaliação de medidas-resumo extraídas de imagens para dosagem de MFI em experimentos de PEP. O repositório engloba desde a fase de exploração de dados até os scripts de implantação e deploy do aplicativo.

---

## 📁 Estrutura do Repositório

O repositório é organizado nas seguintes pastas e arquivos principais:

```text
img-PEP-MFI/
│
├── deploy/                 # Configurações e scripts para implantação da aplicação
├── dev/                    # Scripts e módulos em fase de desenvolvimento
├── notebooks/              # Jupyter Notebooks de análises e testes experimentais
│
├── commit_git.sh           # Script auxiliar para versionamento automatizado no Git
├── estrutura_diretorio.txt # Mapeamento e documentação da estrutura de pastas
├── VERSION                 # Arquivo com a versão atual da aplicação
├── LICENSE                 # Licença MIT
└── README.md               # Documentação principal do repositório
```

---

## 🚀 Como Executar

### 1. Clonar o Repositório

```bash
git clone https://github.com/Laboratorio-de-Analise-de-Dados/img-PEP-MFI.git
cd img-PEP-MFI
```

### 2. Configurar o Ambiente de Desenvolvimento

Crie e ative um ambiente virtual:

```bash
# Criando o ambiente virtual
python -m venv .venv

# Ativando no Linux/macOS:
source .venv/bin/activate

# Ativando no Windows (PowerShell):
.venv\Scripts\Activate.ps1
```

Instale as dependências necessárias para a aplicação (caso utilize um arquivo `requirements.txt`):

```bash
pip install -r requirements.txt
```

---

## 💻 Fluxo de Trabalho

* **Experimentos e Análise de Dados (`notebooks/`):** Utilizado para visualização inicial das imagens, extração de métricas de intensidade e validação estatística.
  ```bash
  jupyter notebook
  ```
* **Desenvolvimento (`dev/`):** Contém os componentes modulares e funções principais da aplicação.
* **Implantação (`deploy/`):** Arquivos prontos para colocar o aplicativo de dosagem de MFI em produção.

---

## 📄 Versionamento e Automação

* **Controle de Versão:** Consulte o arquivo `VERSION` para verificar a versão atual do software.
* **Script Git:** O arquivo `commit_git.sh` pode ser utilizado para padronizar os commits e envios ao repositório remoto:
  ```bash
  chmod +x commit_git.sh
  ./commit_git.sh "Sua mensagem de commit aqui"
  ```

---

## 📜 Licença

Este projeto é distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  <b>Laboratório de Análise de Dados</b>
</p>