# Vizinn App – O Marketplace Hiperlocal para Condomínios e Regiões Próximas

## 🏡 Sobre o Projeto

O **Vizinn** é uma plataforma inovadora que conecta moradores de condomínios e usuários em regiões específicas para compra, venda e oferta de serviços de forma prática e segura. Nosso objetivo é fortalecer a economia local e criar um ambiente confiável para transações entre vizinhos e comunidades próximas.

## 🚀 Foco Inicial

- **Lançamento no Nordeste do Brasil**
- O usuário poderá definir a área de interesse, permitindo transações dentro de seu condomínio ou em locais estratégicos, como universidades, centros comerciais e bairros específicos.

## 📌 Funcionalidades Principais

- ✅ **Marketplace Exclusivo** – Apenas moradores verificados ou usuários em regiões próximas podem anunciar e comprar.
- 🌟 **Anúncios Destaques** – O usuário poderá pagar para destacar seu anúncio e aumentar sua visibilidade.
- 📍 **Filtros de Localização Inteligente** – Busque produtos e serviços dentro do seu condomínio ou em áreas específicas.
- 🔄 **Área de Trocas e Doações** – Incentivo à economia circular dentro das comunidades.
- 🏢 **Painel para Síndicos** – Avisos, regras do condomínio e organização de eventos.
- ⭐ **Avaliações e Reputação** – Sistema de feedback para aumentar a confiança entre os usuários.
- 🔒 **Segurança e Moderação** – Denúncia de anúncios inadequados e validação de identidade.
- 💳 **Opção de Pagamento Integrado** – Facilitando transações seguras dentro do app.
- 📢 **Solicitações Específicas** – Usuários podem publicar demandas específicas, como "Quero um almoço na UFRN".

---

## 🛠 Tecnologias Usadas

### **Front-End (TypeScript)**
- ⚛ **React Native** – Framework para construção de apps móveis nativos.
- 🚀 **Ignite** – Boilerplate para aceleração do desenvolvimento.
- 🛡 **TypeScript** – Tipagem estática para mais segurança e produtividade.
- 🔗 **Axios** – Requisições HTTP eficientes.
- 📲 **React Navigation** – Sistema de navegação flexível.

### **Back-End (Python)**
- ⚡ **FastAPI** – Framework moderno e de alto desempenho para APIs.
- 🗄 **Prisma** – ORM para banco de dados SQL.
- 🔐 **JWT** – Autenticação segura.
- 🏦 **PostgreSQL** – Banco de dados escalável e confiável.

### **Outras Tecnologias**
- 🔔 WebSockets para atualizações em tempo real.
- 🚀 CI/CD para deploy automatizado.

---

## 💡 Oportunidade de Investimento

O **Vizinn App** resolve um problema real e atende a uma demanda crescente por soluções hiperlocais. Buscamos investidores para expandir nossa base de usuários e desenvolver novas funcionalidades.

- 📈 **Modelo de Receita:** Anúncios segmentados, comissão sobre vendas e planos premium.
- 🌍 **Mercado Potencial:** Condomínios e bairros estratégicos no Nordeste do Brasil.
- 🔥 **Diferencial Competitivo:** Segurança, comunidade ativa e experiência otimizada.

---

## 📩 Contato

Se você deseja apoiar essa iniciativa ou fazer parte do projeto, entre em contato:

📧 **Email:** vizinn.app@gmail.com  

---

# 📌 Funcionalidades Essenciais do MVP  

## ✅ 1. Cadastro e Login  
🔹 **Objetivo:** Garantir que apenas moradores ou usuários da região tenham acesso à plataforma.  

📌 **Funcionalidades:**  
- Cadastro por e-mail e senha ou login com Google/Facebook.  
- Validação via código SMS/e-mail para garantir identidade.  
- Confirmação de residência via código do condomínio (opcional).  
- Perfil básico do usuário (nome, foto, localização).  

🔧 **Tecnologias sugeridas:** Firebase Authentication, OAuth, Twilio (SMS).  

---

## ✅ 2. Marketplace Hiperlocal  
🔹 **Objetivo:** Permitir que moradores comprem e vendam produtos/serviços entre si.  

📌 **Funcionalidades:**  
- Criar anúncios com título, descrição, preço e fotos.  
- Seleção de categoria (Ex: Eletrônicos, Serviços, Móveis).  
- Feed de anúncios organizados por localização e categoria.  
- Opção de marcar um item como "Vendido".  

🔧 **Tecnologias sugeridas:** Firestore, PostgreSQL/MongoDB, Cloudinary.  

---

## ✅ 3. Filtros de Localização Inteligente  
🔹 **Objetivo:** Permitir que os usuários encontrem produtos e serviços próximos a eles.  

📌 **Funcionalidades:**  
- Definição manual da área de interesse.  
- Filtragem por distância (ex.: até 2km, até 5km).  
- Busca apenas dentro do condomínio do usuário.  

🔧 **Tecnologias sugeridas:** Google Maps API, GeoFire.  

---

## ✅ 4. Chat Interno entre Usuários  
🔹 **Objetivo:** Facilitar a comunicação entre compradores e vendedores diretamente no app.  

📌 **Funcionalidades:**  
- Mensagens privadas entre usuários.  
- Notificações push para novas mensagens.  
- Indicação de mensagens lidas/não lidas.  

🔧 **Tecnologias sugeridas:** Firestore (tempo real), Firebase Cloud Messaging.  

---

## ✅ 5. Moderação e Segurança  
🔹 **Objetivo:** Criar um ambiente seguro e confiável para os usuários.  

📌 **Funcionalidades:**  
- **Sistema de Denúncias:** Reportar anúncios ou usuários suspeitos.  
- **Regras básicas:** Termos de uso visíveis e aceitos no cadastro.  
- **Bloqueio de usuários:** Moderação ativa.  

🔧 **Tecnologias sugeridas:** Firebase Moderation, moderação manual.  

---

# 📢 Plano de Assinatura no MVP  

## ✅ 1. Modelo de Assinatura  

### **Usuário Gratuito:**  
- Pode postar até **3 anúncios simultâneos**.  
- Cada anúncio pode conter no máximo **2 imagens**.  
- Acesso ao marketplace e chat normalmente.  

### **Usuário Premium (Pago):**  
- **Anúncios ilimitados**.  
- Pode adicionar **mais de 2 imagens** por anúncio.  
- Possibilidade de **destacar anúncios gratuitamente** (X vezes por mês).  
- **Prioridade no suporte** e futuras funcionalidades exclusivas.  

---

## ✅ 2. Implementação da Assinatura  

📌 **Funcionalidades:**  
- Tela de assinatura com detalhes dos benefícios.  
- Sistema de pagamento integrado (**Stripe, Mercado Pago ou App Store/Google Play**).  
- Controle de planos no perfil do usuário.  
- Alerta quando o usuário gratuito atingir o limite de anúncios ou imagens.  

🔧 **Tecnologias sugeridas:**  
- **Stripe / Mercado Pago** (pagamentos recorrentes).  
- **Firebase Firestore** para status da assinatura.  
- **Cloud Functions** para controle de permissões.  

---

## ✅ 3. Experiência do Usuário  
- **Ao tentar criar um 4º anúncio**, um pop-up oferece o upgrade para premium.  
- **Ao tentar adicionar mais de 2 imagens**, uma mensagem alerta sobre a limitação.  
- **Página de “Meus Anúncios”** mostrando a contagem de anúncios ativos.  

---

🚀 **Vizinn App – Transformando Vizinhanças, Conectando Pessoas!**
