# Guia de Execução

Este guia descreve como configurar e executar localmente o projeto HTML/CSS da **Atividade Prática Supervisionada (APS)**.

---

## 1. Pré-requisitos

Antes de iniciar, certifique-se de ter instalado em sua máquina:

- **Git** (para clonar o repositório)
- **Navegador Web** (Chrome, Firefox, Edge etc.)
- **Editor de Texto** (opcional, como VS Code, Sublime, Atom)
- **Python 3.x** (se for usar servidor HTTP local)

---

## 2. Clonando o repositório

1. Abra o terminal ou prompt de comando.
2. Navegue até a pasta onde deseja salvar o projeto:
   ```bash
   cd /caminho/para/pasta
   ```
3. Clone o repositório:
   ```bash
   git clone https://github.com/Sasukezin678/APS.git
   ```
4. Acesse o diretório do projeto:
   ```bash
   cd meu-site-projeto
   ```

---

## 3. Estrutura de Pastas

```
meu-site-projeto/
├── css/
│   └── styles.css       # Arquivo de estilos
├── index.html           # Página principal
├── LICENSE              # Licença GNU GPLv3
├── README.md            # Documentação geral
└── docs/
    └── guia-de-execucao.md  # Este guia
```

---

## 4. Executando localmente

Você pode abrir diretamente o arquivo `index.html` no navegador ou utilizar um servidor HTTP simples para evitar problemas de CORS e rotas relativas.

### 4.1. Abrindo direto no navegador

1. No explorador de arquivos, navegue até a pasta do projeto.
2. Dê um duplo clique em `index.html`.
3. O navegador abrirá a página localmente.

### 4.2. Utilizando servidor HTTP com Python

1. Certifique-se de ter o Python instalado (versão 3.x).
2. No terminal, estando na raiz do projeto, execute:
   ```bash
   python3 -m http.server 8000
   ```
3. Abra o navegador e acesse:
   ```
   http://localhost:8000/
   ```
4. Para parar o servidor, pressione `Ctrl + C` no terminal.

---

## 5. Acessando o site publicado

Caso prefira testar a versão online:

- Acesse: [https://sasukezin678.github.io/APS/](https://sasukezin678.github.io/APS/)

---

## 6. Referências

- [README.md](../README.md)
- [LICENSE](../LICENSE)

---

*Pronto! Agora você pode explorar e testar o projeto localmente. Bons estudos!*
