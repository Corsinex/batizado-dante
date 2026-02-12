# 🎉 Site de Confirmação de Presença - Batizado Dante Augusto Corsino

Site completo e responsivo para confirmação de presença no batizado e 1º aniversário do Dante.

## ✨ Funcionalidades

- ✅ Formulário completo de confirmação de presença
- 📱 100% Responsivo (funciona em celulares, tablets e desktop)
- 💬 Integração direta com WhatsApp
- 👥 Campo para informar acompanhantes
- 💌 Campo opcional para mensagens
- 🎨 Design elegante e moderno
- ⚡ Carregamento rápido
- 🔗 Compatível com QR Code

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique em **"New"** (Novo) ou no botão **"+"** no canto superior direito
3. Escolha **"New repository"**
4. Preencha:
   - **Repository name:** `batizado-dante` (ou outro nome de sua preferência)
   - Marque como **Public** (Público)
   - ✅ Marque **"Add a README file"**
5. Clique em **"Create repository"**

### Passo 2: Fazer Upload do Arquivo

1. No seu repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste o arquivo `index.html` ou clique para selecionar
3. Adicione uma mensagem de commit: `"Adicionar site de confirmação"`
4. Clique em **"Commit changes"**

### Passo 3: Ativar GitHub Pages

1. No repositório, clique em **"Settings"** (Configurações)
2. No menu lateral esquerdo, clique em **"Pages"**
3. Em **"Source"** (Fonte):
   - Selecione **"Deploy from a branch"**
   - Branch: **"main"** ou **"master"**
   - Pasta: **"/ (root)"**
4. Clique em **"Save"**
5. Aguarde alguns minutos (geralmente 1-3 minutos)

### Passo 4: Acessar o Site

Seu site estará disponível em:
```
https://SEU-USUARIO.github.io/batizado-dante/
```

Por exemplo, se seu usuário é `cesaraugusto`, o link será:
```
https://cesaraugusto.github.io/batizado-dante/
```

## 📱 Como Criar QR Code

1. Acesse um gerador de QR Code gratuito:
   - [QR Code Generator](https://www.qr-code-generator.com/)
   - [QR Code Monkey](https://www.qrcode-monkey.com/)
   - [QRCode.io](https://qrcode.io/)

2. Cole o link do seu site GitHub Pages

3. Personalize (opcional):
   - Adicione cores
   - Adicione logo no centro
   - Ajuste o tamanho

4. Faça o download do QR Code em alta resolução

5. Use o QR Code nos convites impressos ou digitais

## 🔧 Personalização

Para editar o site:

1. No repositório, clique no arquivo `index.html`
2. Clique no ícone de lápis (Edit)
3. Faça suas alterações
4. Role até o final, adicione uma mensagem de commit
5. Clique em **"Commit changes"**

### O que você pode personalizar:

- **Data e horário:** Localize "Em breve será definida" e "A confirmar"
- **Cores:** Altere as variáveis CSS em `:root`
- **Textos:** Modifique qualquer texto do convite
- **WhatsApp:** O número já está configurado como `5531986805607`

## 📞 Número de WhatsApp

O número já está configurado no código:
```javascript
const whatsappNumber = '5531986805607';
```

Todas as confirmações serão enviadas diretamente para este número via WhatsApp.

## 🎨 Design

- **Fontes:** Cormorant Garamond e Montserrat (Google Fonts)
- **Cores:** Azul (#0B7FA6) e Dourado (#D4A574)
- **Estilo:** Elegante, suave e profissional
- **Animações:** Sutis e suaves
- **Responsivo:** Adapta-se a qualquer tamanho de tela

## ✅ Compatibilidade

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera
- ✅ Navegadores mobile (iOS e Android)

## 📱 Funcionamento via QR Code

O site foi desenvolvido para funcionar perfeitamente quando acessado via QR Code:

1. Visitante escaneia o QR Code
2. Abre automaticamente no navegador do celular
3. Preenche o formulário
4. Clica em "Confirmar via WhatsApp"
5. Abre o WhatsApp com a mensagem pré-formatada
6. Envia a confirmação

## 🆘 Suporte

Se tiver alguma dúvida ou problema:

1. Verifique se o arquivo está nomeado exatamente como `index.html`
2. Certifique-se de que o repositório está público
3. Aguarde alguns minutos após ativar o GitHub Pages
4. Limpe o cache do navegador (Ctrl + F5)

## 📝 Licença

Livre para uso pessoal.

---

**Desenvolvido com 💙 para Dante Augusto Corsino**
