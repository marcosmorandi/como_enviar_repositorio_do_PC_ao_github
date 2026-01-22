## 1️⃣ Se ainda não estiver instalado, instalar o Git/GitHub Desktop no PC. Pode verificar a instalação e versão pelo comando "git --version" no Terminal. Tem duas opções principais para instalar e usar o Git/GitHub Desktop no PC

---

## 1. Instalar o **Git** (linha de comando)
O Git é a ferramenta essencial para trabalhar com repositórios.  
### Passos:
1. Vá até o site oficial: [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Baixe a versão para **Windows**.
3. Execute o instalador e siga as instruções (pode deixar as opções padrão).
4. Depois de instalado, abra o **Prompt de Comando** ou **PowerShell** e digite:
   ```bash
   git --version
   ```
   Se aparecer a versão, significa que deu certo.

---

## 2. Instalar o **GitHub Desktop** (interface gráfica)
Se você prefere algo mais visual e simples:
1. Acesse: [https://desktop.github.com](https://desktop.github.com).
2. Baixe e instale o **GitHub Desktop**.
3. Faça login com sua conta GitHub.
4. Agora você pode clonar repositórios, criar commits e enviar alterações sem precisar usar comandos.

---

## Qual escolher?
- **Git (linha de comando):** mais flexível e usado profissionalmente.
- **GitHub Desktop:** ideal para iniciantes ou quem prefere interface gráfica.

<br><br>
==========
<br><br>

## 2️⃣ Fazer upload de um projeto pronto para o GitHub. Passo a passo para subir seu projeto no GitHub

---

### 1. Criar um repositório no GitHub
- Acesse [GitHub](https://github.com).
- Clique em **New Repository**.
- Dê um nome ao repositório (ex: `meu-projeto`).
- Escolha se será público ou privado.
- Clique em **Create Repository**.

---

### 2. Preparar seu projeto localmente
No seu computador:
- Certifique-se de que o projeto está em uma pasta organizada.
- Abra o **terminal** ou **Git Bash** dentro dessa pasta.

---

### 3. Inicializar o Git
```bash
git init
```
Isso transforma sua pasta em um repositório Git.

---

### 4. Conectar ao repositório remoto
Copie a URL do repositório que você criou no GitHub (ex: `https://github.com/usuario/meu-projeto.git`) e rode:
```bash
git remote add origin https://github.com/usuario/meu-projeto.git
```

---

### 5. Adicionar os arquivos
```bash
git add .
```
Isso adiciona todos os arquivos da pasta ao Git.

---

### 6. Fazer o commit
```bash
git commit -m "Primeiro commit do projeto"
```

---

### 7. Enviar para o GitHub
```bash
git branch -M main
git push -u origin main
```

---

### Observação
- Se for a primeira vez que você está dando `push`, pode ser necessário configurar seu usuário:
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@exemplo.com"
  ```
- Escolher entre as opções de login no Git.

---

### Resultado
Agora seu projeto estará disponível no GitHub!  
Você pode verificar acessando o repositório pelo navegador.

<br><br>
==========
<br><br>

## 3️⃣ Para mandar as edições do seu projeto GitHub

### 1. Verificar o estado atual do repositório, se é necessário ou não o próximo commit
No terminal:
```bash
git status
```

---

### 2. Se neceásrio, adicionar todas as alterações (novos arquivos, arquivos modificados e até exclusões) que estão na pasta do projeto para serem incluídas no próximo commit
No terminal:
```bash
git add .
```

---

### 3. Registrar as alterações preparadas com "git add" no histórico do Git, junto com uma mensagem explicativa
No terminal:
```bash
git commit -m "mensagem"
```

---

### 4. Enviar os commits que locais para o repositório remoto
No terminal:
```bash
git push 
```

---

### 5. Opcionalmente para limpar o terminal
No terminal:
```bash
clear
```

---

### 6. Ver o histórico dos últimos comandos para agilizar ou relembrar
No terminal:
usar as setas para cima ⬆️ ou para baixo ⬇️ no teclado

---

### Observação
No VS Code, também dá para clicar em **Source Control** (ícone de 3 círculos conectados por linhas) que faz o procedimento de maneira mais intuitiva com interface gráfica para iniciantes.

---

### Resultado
Abrir o repositório no navegador e se certificar que as mudanças apareceram.
