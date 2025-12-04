# Torre de Hanói - Trabalho Final de Lógica

## 📦 Conteúdo da Pasta

Esta pasta contém todos os arquivos necessários para colocar o site no ar:

- **index.html** - Página principal do trabalho (renomeada de TrabalhoFinalLogica.html)
- **automato_hanoi_n.png** - Diagrama do autômato finito
- **README.md** - Este arquivo

## 🚀 Como fazer deploy no GitHub Pages

### Passo 1: Criar repositório no GitHub
1. Acesse https://github.com/new
2. Nomeie o repositório (ex: `trabalho-final-logica`)
3. Deixe como **Public**
4. Clique em **Create repository**

### Passo 2: Fazer upload dos arquivos
Existem duas formas:

#### Opção A: Upload via interface web (mais fácil)
1. No repositório criado, clique em **Add file** → **Upload files**
2. Arraste todos os arquivos desta pasta para a página
3. Clique em **Commit changes**

#### Opção B: Upload via Git (recomendado)
```bash
cd TrabalhoFinalLogica-Deploy
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

### Passo 3: Ativar GitHub Pages
1. No repositório, vá em **Settings** → **Pages**
2. Em **Source**, selecione **main** branch
3. Clique em **Save**
4. Aguarde alguns segundos

### Passo 4: Acessar o site
Seu site estará disponível em:
```
https://SEU_USUARIO.github.io/SEU_REPOSITORIO/
```

## ✨ Recursos da Página

- Design moderno com glassmorphism e gradientes
- Totalmente responsivo
- Animações suaves
- Sem dependências locais (usa CDN para Tailwind e fontes)
- Pronto para produção

## 📝 Observações

- O arquivo foi renomeado para `index.html` pois o GitHub Pages usa esse nome como página inicial por padrão
- Todas as dependências (Tailwind CSS, Google Fonts) são carregadas via CDN
- O site funciona 100% offline depois do primeiro carregamento (exceto as fontes)

---

**Desenvolvido por:** Rômulo Henrique Zanfran Braun  
**Disciplina:** Lógica para Computação (2025.2)  
**Instituição:** IFC - São Bento do Sul
