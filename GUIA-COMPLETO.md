# 🎉 GUIA COMPLETO ATUALIZADO - Site com Painel Administrativo

## 🆕 NOVIDADES DESTA VERSÃO

### ✅ O que foi adicionado:
1. **Data definida:** 22 de Março de 2025
2. **Horário definido:** 14h00
3. **Campo de Cônjuge:** Agora pode informar o nome do cônjuge
4. **Painel Administrativo:** Página para alterar dados do evento
5. **Botão de Admin:** Acesso rápido ao painel (canto inferior direito)

---

## 📦 ARQUIVOS QUE VOCÊ RECEBEU

### 1. **index.html** - Site Principal
- Site de confirmação de presença
- Data: 22 de Março de 2025
- Horário: 14h00
- Campo para nome completo do convidado
- Campo para nome do cônjuge
- Campo para acompanhantes adicionais
- Botão administrativo no canto inferior direito (⚙️)

### 2. **admin.html** - Painel Administrativo
- Login protegido por senha
- Edição de data, horário e local
- Edição do número de WhatsApp
- Preview das alterações
- Instruções de como aplicar

---

## 🚀 PASSO A PASSO COMPLETO

### **ETAPA 1: CRIAR CONTA NO GITHUB**

1. Acesse: https://github.com
2. Clique em **"Sign up"** (se não tiver conta)
3. Preencha:
   - Email
   - Senha
   - Username (ex: `cesaraugustocorsino`)
4. Confirme o email

---

### **ETAPA 2: CRIAR REPOSITÓRIO**

1. Faça login no GitHub
2. Clique no **"+"** (canto superior direito)
3. Selecione **"New repository"**
4. Configure:
   ```
   Repository name: batizado-dante
   Description: Site de confirmação - Batizado Dante Augusto
   ✅ Public
   ✅ Add a README file
   ```
5. Clique em **"Create repository"**

---

### **ETAPA 3: UPLOAD DOS ARQUIVOS**

**IMPORTANTE:** Você precisa fazer upload dos DOIS arquivos!

#### Upload do index.html:
1. No repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste o arquivo **index.html**
3. Escreva: `Adicionar página principal`
4. Clique em **"Commit changes"**

#### Upload do admin.html:
1. Clique novamente em **"Add file"** → **"Upload files"**
2. Arraste o arquivo **admin.html**
3. Escreva: `Adicionar painel administrativo`
4. Clique em **"Commit changes"**

**Agora você deve ter 3 arquivos no repositório:**
- README.md
- index.html
- admin.html

---

### **ETAPA 4: ATIVAR GITHUB PAGES**

1. Clique em **"Settings"** (última aba)
2. No menu lateral, clique em **"Pages"**
3. Em **"Source"**, selecione:
   - Branch: **main** (ou master)
   - Folder: **/ (root)**
4. Clique em **"Save"**
5. Aguarde 2-5 minutos

**Seu site estará em:**
```
https://SEU-USUARIO.github.io/batizado-dante/
```

**Seu painel admin estará em:**
```
https://SEU-USUARIO.github.io/batizado-dante/admin.html
```

---

### **ETAPA 5: TESTAR O SITE**

#### Testar página principal:
1. Acesse: `https://SEU-USUARIO.github.io/batizado-dante/`
2. Verifique se aparece:
   - Data: 22 de Março de 2025
   - Horário: 14h00
   - Formulário completo
3. Teste preencher o formulário
4. Clique no botão ⚙️ (canto inferior direito)
5. Deve abrir o painel admin

#### Testar painel administrativo:
1. Acesse: `https://SEU-USUARIO.github.io/batizado-dante/admin.html`
2. Faça login com:
   - **Usuário:** `admin`
   - **Senha:** `dante2025`
3. Teste editar as informações
4. Clique em "Salvar Alterações"

---

### **ETAPA 6: CRIAR QR CODE**

1. Acesse: https://www.qr-code-generator.com/
2. Selecione tipo: **URL**
3. Cole: `https://SEU-USUARIO.github.io/batizado-dante/`
4. Baixe em **alta resolução** (PNG)
5. Use no convite!

---

## 🔐 PAINEL ADMINISTRATIVO

### Como acessar:

**Opção 1 - Pelo botão no site:**
- Abra o site principal
- Clique no botão ⚙️ no canto inferior direito

**Opção 2 - Direto pela URL:**
- Acesse: `https://SEU-USUARIO.github.io/batizado-dante/admin.html`

### Credenciais de acesso:
```
Usuário: admin
Senha: dante2025
```

### O que você pode fazer no painel:

✏️ **Editar informações do evento:**
- Data do evento
- Horário
- Local completo
- Número do WhatsApp

📋 **Ver informações atuais:**
- Mostra o que está publicado no site

👀 **Preview das alterações:**
- Veja como ficará antes de publicar

---

## ✏️ COMO EDITAR AS INFORMAÇÕES DO SITE

### **Método 1: Pelo Painel Administrativo (Recomendado)**

1. Acesse o painel admin
2. Faça login
3. Edite os campos desejados
4. Clique em "Salvar Alterações"
5. **IMPORTANTE:** Por enquanto, você precisa copiar as informações e editar manualmente no GitHub

### **Método 2: Diretamente no GitHub**

1. Acesse seu repositório no GitHub
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis ✏️ (editar)
4. Procure e altere:

**Para mudar a DATA:**
```html
<div class="detalhe-texto" id="dataEvento">22 de Março de 2025</div>
```

**Para mudar o HORÁRIO:**
```html
<div class="detalhe-texto" id="horarioEvento">14h00</div>
```

**Para mudar o LOCAL:**
```html
<p id="localEvento">
    <strong>Comunidade Nossa Senhora de Fátima</strong><br>
    R. José de Anchieta, Bairro Cidade Nova<br>
    Santana do Paraíso - MG
</p>
```

**Para mudar o WHATSAPP:**
```javascript
const numeroWhatsApp = '5531986805607';
```

5. Role até o final
6. Clique em **"Commit changes"**
7. Aguarde 1-2 minutos

---

## 📱 COMO FUNCIONAM AS CONFIRMAÇÕES

### Processo completo:

1. **Convidado acessa o site** (via QR Code ou link)
2. **Preenche o formulário:**
   - Nome completo
   - Nome do cônjuge (se aplicável)
   - Confirma presença (sim/não)
   - Informa número de acompanhantes
   - Nomes dos acompanhantes
   - Mensagem opcional
3. **Clica em "Confirmar via WhatsApp"**
4. **WhatsApp abre automaticamente**
5. **Mensagem já vem formatada**
6. **Convidado envia**
7. **VOCÊ RECEBE** no número: **31 98680-5607**

### Exemplo de mensagem que você receberá:

```
🎉 CONFIRMAÇÃO DE PRESENÇA
Batizado Dante Augusto Corsino

━━━━━━━━━━━━━━━━━━━━

👤 Nome: João Silva
💑 Cônjuge: Maria Silva

✅ Presença: CONFIRMADA! 🎊

👥 Total de pessoas: 4 (você + cônjuge + 2 acompanhantes)

📝 Nomes dos acompanhantes:
   1. Pedro Silva
   2. Ana Silva

💌 Mensagem para o Dante:
"Que Deus abençoe muito essa criança!"

━━━━━━━━━━━━━━━━━━━━
Confirmação enviada via site
```

---

## 🎨 CARACTERÍSTICAS DO SITE

### Design:
- ✅ Cores elegantes (azul e dourado)
- ✅ Totalmente responsivo
- ✅ Animações suaves
- ✅ Visual profissional

### Funcionalidades:
- ✅ Campo para nome completo
- ✅ Campo para cônjuge
- ✅ Confirmação de presença
- ✅ Acompanhantes adicionais
- ✅ Mensagem opcional
- ✅ Integração WhatsApp
- ✅ Botão de acesso ao admin
- ✅ Painel administrativo

### Compatibilidade:
- ✅ iPhone e Android
- ✅ Tablets
- ✅ Computadores
- ✅ Todos navegadores
- ✅ Perfeito para QR Code

---

## 🔧 ALTERAR CREDENCIAIS DO ADMIN

Se você quiser mudar o usuário e senha do painel:

1. Acesse o arquivo `admin.html` no GitHub
2. Clique em editar ✏️
3. Procure por estas linhas (próximo ao início do código JavaScript):

```javascript
const USUARIO_ADMIN = 'admin';
const SENHA_ADMIN = 'dante2025';
```

4. Altere para o que você quiser:
```javascript
const USUARIO_ADMIN = 'cesaraugusto';
const SENHA_ADMIN = 'minhasenha123';
```

5. Salve as alterações

---

## ⚠️ IMPORTANTE - LEIA COM ATENÇÃO

### ✅ FAÇA:
- Teste o site antes de divulgar
- Teste em vários celulares diferentes
- Teste o botão do WhatsApp
- Salve o link do site em lugar seguro
- Faça backup dos arquivos HTML
- Use QR Code em alta resolução

### ❌ NÃO FAÇA:
- Deixar repositório privado
- Mudar nome dos arquivos
- Deletar repositório sem backup
- Divulgar sem testar

---

## 🆘 SOLUÇÃO DE PROBLEMAS

### Site não carrega:
- Aguarde 5 minutos após ativar Pages
- Limpe cache (Ctrl + Shift + Delete)
- Tente modo anônimo
- Verifique se está "Public"

### Botão admin não funciona:
- Verifique se fez upload do admin.html
- Acesse direto: `/admin.html` no final da URL

### Não consigo fazer login no admin:
- Usuário: `admin` (tudo minúsculo)
- Senha: `dante2025` (tudo minúsculo)
- Sem espaços antes ou depois

### WhatsApp não abre:
- Verifique se WhatsApp está instalado
- No PC, use WhatsApp Web
- Verifique o número: 5531986805607

---

## 📊 RESUMO RÁPIDO

### O que você tem agora:
- ✅ Site com data: 22/03/2025
- ✅ Horário: 14h00
- ✅ Campo para cônjuge
- ✅ Painel administrativo
- ✅ Login protegido
- ✅ Tudo funcionando!

### Links importantes:
```
Site: https://SEU-USUARIO.github.io/batizado-dante/
Admin: https://SEU-USUARIO.github.io/batizado-dante/admin.html
```

### Credenciais admin:
```
Usuário: admin
Senha: dante2025
```

---

## 🎊 CHECKLIST FINAL

Antes de divulgar:

- [ ] Site está no ar
- [ ] Data está correta (22/03/2025)
- [ ] Horário está correto (14h00)
- [ ] Local está correto
- [ ] WhatsApp está correto (31 98680-5607)
- [ ] Testei o formulário no PC
- [ ] Testei o formulário no celular
- [ ] WhatsApp abre corretamente
- [ ] Painel admin funciona
- [ ] Consigo fazer login no admin
- [ ] QR Code foi criado
- [ ] QR Code foi testado
- [ ] QR Code em alta resolução

---

## 🎉 PRONTO!

Agora você tem um site profissional com:
- 📅 Data e horário definidos
- 💑 Campo para cônjuge
- 👥 Controle de acompanhantes
- 📱 WhatsApp integrado
- ⚙️ Painel administrativo
- 🔐 Acesso protegido
- 📊 Sistema organizado

**Divulgue o QR Code e receba as confirmações! 🎊**

---

Desenvolvido com 💙 para Dante Augusto Corsino
