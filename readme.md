☝️#☝️ Se ainda não estiver instalado, instalar o Git/GitHub Desktop no PC, pode verificar a instalação e versão pelo comando "git --version" no terminal.
# Você tem duas opções principais para instalar e usar o Git/GitHub Desktop no seu PC 🖥️:

---

## 🔹 1. Instalar o **Git** (linha de comando)
O Git é a ferramenta essencial para trabalhar com repositórios.  
### Passos:
1. Vá até o site oficial: [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Baixe a versão para **Windows**.
3. Execute o instalador e siga as instruções (pode deixar as opções padrão).
4. Depois de instalado, abra o **Prompt de Comando** ou **PowerShell** e digite:
   ```bash
   git --version
   ```
   Se aparecer a versão, significa que deu certo ✅.

---

## 🔹 2. Instalar o **GitHub Desktop** (interface gráfica)
Se você prefere algo mais visual e simples:
1. Acesse: [https://desktop.github.com](https://desktop.github.com).
2. Baixe e instale o **GitHub Desktop**.
3. Faça login com sua conta GitHub.
4. Agora você pode clonar repositórios, criar commits e enviar alterações sem precisar usar comandos.

---

## ✨ Qual escolher?
- **Git (linha de comando):** mais flexível e usado profissionalmente.
- **GitHub Desktop:** ideal para iniciantes ou quem prefere interface gráfica.

---
---

✌️#✌️ Fazer upload de um projeto pronto ou em andamento para o GitHub:

---

## 📂 Passo a passo para subir seu projeto no GitHub

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

## ✅ Resultado
Agora seu projeto estará disponível no GitHub!  
Você pode verificar acessando o repositório pelo navegador.

---
