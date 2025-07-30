# 🚀 Criando uma Máquina Virtual no Microsoft Azure

Este repositório faz parte do desafio proposto pela DIO para consolidar os conhecimentos sobre **máquinas virtuais no Azure**, aplicando os conceitos aprendidos em um ambiente real, com documentação clara e estruturada.

---

## 🎯 Objetivos do Desafio

- Aplicar, na prática, os conceitos de computação em nuvem com foco em **IaaS (Infraestrutura como Serviço)**.
- Criar uma **Máquina Virtual (VM)** no Microsoft Azure.
- Documentar o processo técnico de forma objetiva e visual.
- Utilizar o **GitHub como ferramenta de portfólio técnico**.

---

## 🧠 O que você vai aprender

- Conceitos básicos de Cloud Computing com foco em **Azure**.
- Diferença entre **CapEx e OpEx**.
- Criação de recursos de forma manual no portal do Azure.
- Estrutura e uso das **máquinas virtuais** (VMs).
- Noções de segurança e conectividade.

---

## 🛠️ Pré-requisitos

- Conta Microsoft com acesso ao [Azure Portal](https://portal.azure.com/)
- Conhecimento introdutório em cloud (Azure, redes, e sistemas operacionais)
- Acesso à [plataforma da DIO](https://web.dio.me/)
- Git e GitHub instalados (opcional, mas recomendado)

---

## 🧾 Etapas do Processo

> Abaixo está o passo a passo para a criação de uma máquina virtual no Azure com espaço reservado para screenshots.

### 1. Acesse o Portal do Azure

Acesse: https://portal.azure.com/

📷 **[Espaço para imagem:](`/images/1-portal.png`)**
---

### 2. Vá até **"Máquinas Virtuais"** e clique em **"Criar"**

Escolha:  
- **Máquina Virtual do Windows (ou Linux)**  
- Grupo de recursos (crie um se necessário)  
- Nome da máquina  
- Região (ex: Brazil South)  
- Imagem (ex: Windows Server 2019)

📷 **[Espaço para imagem:](`/images/2-configuracao-basica.png`)**

---

### 3. Defina as Credenciais de Acesso

- Nome de usuário
- Senha segura (recomenda-se letras, números e símbolos)

📷 **[`/images/3-credenciais.png`]**

---

### 4. Configure o Tamanho e Tipo da Instância

- Escolha um tamanho compatível com sua cota de uso gratuito (ex: B1s)

📷 **[`/images/4-tamanho-vm.png`]**

---

### 5. Configure o Acesso (Portas)

- Permitir RDP (porta 3389) para acessar via Área de Trabalho Remota (Windows)
- Opcional: configurar regra de firewall

---

### 6. Revisar e Criar

- Revise todas as configurações
- Clique em **Criar**
- Aguarde a implantação

---

### 7. Conectar à Máquina Virtual

- Após a criação, clique em **"Conectar"**
- Baixe o arquivo `.rdp` e entre com o usuário e senha definidos


---

## 📁 Organização do Repositório
📦 azure-vm-desafio
┣ 📂 images
┃ ┣ 📜 1-portal.png
┃ ┣ 📜 2-configuracao-basica.png
┃ ┗ ...
┣ 📜 README.md
┗ 📜 notas.txt (opcional)

## 🔗 Recursos Úteis

- [Criar uma máquina virtual do Windows no Azure (Microsoft)](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- [GitHub Docs - Markdown](https://docs.github.com/pt/get-started/writing-on-github)
- [Guia Rápido GitHub (DIO)](https://github.com/digitalinnovationone/github-quickstart)

---

## ✅ Conclusão

Com este desafio, consolidamos o entendimento prático sobre a criação de VMs no Azure e desenvolvemos habilidades fundamentais para o trabalho com infraestrutura em nuvem. Além disso, utilizamos o GitHub como vitrine técnica para portfólio e documentação.

---

## ✍️ Autor

**Felipe [@felkj]**  
Estudante de Análise e Desenvolvimento de Sistemas  
Desenvolvedor web com foco em tecnologias modernas e cloud

---

*“Não pule etapas. Documente seu processo. E use cada desafio como uma oportunidade de crescimento.”*

