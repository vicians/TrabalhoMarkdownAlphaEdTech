# 🌐 Fundamentos da Internet e Redes

---

### 🏗️ Evolução e Estrutura

* **Origem (ARPANET):** A rede nasceu descentralizada e militar, evoluindo para a Internet global através da padronização do TCP/IP.

* **Topologias:** Formatos como estrela, malha e híbrida definem a conexão física/lógica, impactando a confiabilidade e escalabilidade.

* **Backbones:** São as grandes vias de fibra óptica que transportam o tráfego mundial em altíssima velocidade entre continentes 🌍.

---

### 📦 Protocolos e Endereçamento

* **TCP:** Protocolo focado em confiabilidade, garantindo que os dados cheguem completos e na ordem certa ✔️.

* **UDP:** Focado em velocidade (streaming/jogos), aceita pequenas perdas para evitar atrasos ⚡.

* **Endereços IP:** A identidade da máquina na rede. O IPv4 (32 bits) está esgotado, dando lugar ao IPv6 (128 bits).

* **Portas:** Direcionam o tráfego para o serviço correto dentro do servidor (ex: porta 443 para HTTPS).

* **DNS:** O "catálogo" que traduz nomes amigáveis (sites) para endereços IP numéricos 🔎.

---

### 🔐 Segurança e Privacidade

* **VPNs:** Criam túneis privados e criptografados sobre a rede pública para proteger o acesso.

* **HTTPS (SSL/TLS):** Protocolo que criptografa os dados em trânsito, impedindo a leitura por interceptadores.

* **Certificados Digitais:** Validam a identidade real dos servidores, garantindo que você não está em um site falso.

* **LGPD:** Legislação que exige responsabilidade e transparência no tratamento de dados pessoais dos usuários.

---

### 🚀 Tecnologias Emergentes

* **IoT (Internet das Coisas):** Conecta objetos do dia a dia (sensores, casas inteligentes) à rede mundial 🏠.

* **Web 3.0 e Blockchain:** Propõem uma internet descentralizada, com registros imutáveis e maior segurança.

* **IA e Machine Learning:** Automatizam a detecção de ameaças e otimizam o desempenho da rede em tempo real 🤖.

<br>

# 🐙 Fundamentos de Git e GitHub

---

### 🏗️ Conceitos e Diferenças

* **Git vs. GitHub:** O Git é o sistema de versionamento que roda na sua máquina já o GitHub, é a plataforma na nuvem que hospeda o código e facilita a colaboração.

* **Repositório (Repo):** É a pasta do projeto onde o Git monitora todas as mudanças. Pode ser local (no seu PC) ou remoto (no servidor).

---

### 💻 Comandos Essenciais

* **git init / git clone:** `init` cria um novo repositório do zero; `clone` baixa para sua máquina um projeto que já existe na nuvem.

* **git add:** Move os arquivos modificados para a "Staging Area", preparando-os para serem salvos.

* **git commit:** Salva efetivamente as mudanças preparadas, criando um ponto na história com uma mensagem explicativa (`-m`) ✔️.

* **git status:** O comando "bússola" que mostra quais arquivos foram alterados, quais estão preparados e o que está pendente.

* **git push / git pull:** `push` envia seus commits locais para o GitHub; `pull` traz as atualizações da nuvem para o seu computador ☁️.

---

### 🤝 Fluxo de Trabalho e Colaboração

* **Branches (Ramos):** Linhas paralelas de desenvolvimento que permitem criar novas funções sem quebrar o código principal (Main/Master).

* **Merge:** A ação de fundir uma branch secundária de volta na principal quando o trabalho está pronto.

* **Pull Request (PR):** Um pedido formal para integrar suas alterações ao projeto, permitindo que colegas revisem o código antes de aceitar.

---

### 🛡️ Boas Práticas e Organização

* **.gitignore:** Um arquivo essencial que lista o que o Git não deve rastrear (como senhas, arquivos de sistema ou pastas de build) 🙈.

* **Conflitos:** Ocorrem quando duas pessoas editam a mesma linha de código; o Git pausa e pede para você escolher qual versão manter.
```