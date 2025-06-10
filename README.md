# Auto Start App

Este projeto automatiza a abertura de programas como Roblox Studio, Discord e Obsidian ao ser executado. O código principal está localizado em `src/main.py` e utiliza a biblioteca `pyautogui` para realizar as automações.

## Estrutura do Projeto

```
auto-start-app
├── src
│   └── main.py
├── requirements.txt
└── README.md
```

## Instalação

Para instalar as dependências necessárias, execute o seguinte comando:

```
pip install -r requirements.txt
```

## Como Configurar para Iniciar Automaticamente

Para que o aplicativo seja executado automaticamente ao ligar o computador, siga estas etapas:

1. **Windows**:
   - Pressione `Win + R`, digite `shell:startup` e pressione `Enter`.
   - Crie um atalho para o arquivo `main.py` dentro da pasta de inicialização.
   - Para criar um atalho, clique com o botão direito no arquivo `main.py`, selecione "Criar atalho" e mova o atalho para a pasta de inicialização.

2. **Linux**:
   - Abra o terminal e digite `gnome-session-properties` para abrir o gerenciador de aplicativos de inicialização.
   - Clique em "Adicionar" e preencha os campos:
     - Nome: Auto Start App
     - Comando: `python3 /caminho/para/o/projeto/src/main.py`
     - Comentário: Inicia o Auto Start App.
   - Clique em "Adicionar" e depois em "Fechar".

3. **Mac**:
   - Abra "Preferências do Sistema" e vá para "Usuários e Grupos".
   - Selecione seu usuário e clique na aba "Itens de Início".
   - Arraste o arquivo `main.py` para a lista ou clique no botão "+" e selecione o arquivo.

## Uso

Após a configuração, o aplicativo será iniciado automaticamente ao ligar o computador, abrindo os programas configurados.
