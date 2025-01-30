

# Danilo Conceição

# 👋 Olá, sou o Danilo Conceição!

🌐 Especialista em Infraestrutura de Redes e Segurança  
💡 Certificado CCNA, CCNP e atualmente focado na certificação SD-WAN.  
🚀 Apaixonado por construir soluções inovadoras para redes de computadores e infraestrutura. Sempre busco aprender e aplicar as melhores práticas para garantir redes mais seguras e eficientes.  
📚 Compartilho meus laboratórios, projetos e aprendizados aqui no meu GitHub.

---

## 📚 Certificações

<div style="display: flex; flex-wrap: wrap;">
  <img src="https://images.credly.com/size/340x340/images/8b0ca811-bd98-4083-ba50-512ab9f6262b/CCNPENCOR__1_.png" height="80" style="margin-right: 10px;">
  <img src="https://images.credly.com/size/340x340/images/3bb1a127-e4e4-47ac-b83f-6a9fbf343f00/CCNP_ENARSI.png" height="80" style="margin-right: 10px;">
  <img src="https://images.credly.com/size/340x340/images/f4ccdba9-dd65-4349-baad-8f05df116443/CCNASRWE__1_.png" height="80" style="margin-right: 10px;">
  <img src="https://images.credly.com/size/340x340/images/70d71df5-f3dc-4380-9b9d-f22513a70417/CCNAITN__1_.png" height="80" style="margin-right: 10px;">
  <img src="https://images.credly.com/size/340x340/images/0a6d331e-8abf-4272-a949-33f754569a76/CCNAENSA__1_.png" height="80" style="margin-right: 10px;">
  <img src="https://images.credly.com/size/340x340/images/58c6a1ff-4788-4be9-a71e-7643ec7d72e8/2ccb2ec4-fc30-4498-abef-1d1c05637fab.png" height="80">
</div>

---

## 🛠️ Tecnologias que eu uso

<div style="display: flex; justify-content: space-around; align-items: center; margin-bottom: 20px">
  <img align="center" alt="Python" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <p>Python: Linguagem de programação versátil para automação e scripts.</p>
  <img align="center" alt="Git" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg">
  <p>Git: Ferramenta essencial para controle de versão e colaboração em projetos.</p>
  <img align="center" alt="VMware" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vsphere/vsphere-original.svg">
  <p>VMware: Plataforma de virtualização de servidores e redes.</p>
  <img align="center" alt="Docker" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg">
  <p>Docker: Contêineres para desenvolvimento e execução de aplicações em ambientes isolados.</p>
  <img align="center" alt="Linux" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg">
  <p>Linux: Sistema operacional robusto e amplamente utilizado em ambientes de rede.</p>
</div>

---

## 🌍 Vamos conectar?

<div style="display: flex; justify-content: space-evenly; align-items: center;">
  <a href="https://github.com/ConceicaoD10" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="mailto:daniloideconceicao@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/in/danilo-conceição" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
</div>

---

## 📈 Estatísticas do GitHub

![Danilo's GitHub stats](https://github-readme-stats.vercel.app/api?username=ConceicaoD10&show_icons=true&theme=radical)

<p align="center">Aqui você pode ver um resumo das minhas contribuições para a comunidade open-source.</p>

---

⚡ Fun fact: Quando não estou trabalhando com redes, estou aprendendo novas tecnologias e sempre em busca de maneiras inovadoras de resolver problemas!

---

## 📁 Meus Projetos

- [Projeto A](link_do_repositorio) - Descrição do projeto A.
- [Projeto B](link_do_repositorio) - Descrição do projeto B.

## 📑 Publicações

- [Artigo sobre Redes Avançadas](link_do_artigo) - Discussão sobre protocolos avançados de redes.

🚀 Agradeço pela visita! Fique à vontade para explorar meus projetos. 🙂





# Definir nome do repositório
REPO="Laboratorio-BGP101"
GITHUB_USER="ConceicaoD10"

# Criar diretório do repositório e entrar nele
mkdir "$REPO"
cd "$REPO"

# Inicializar repositório Git
git init

# Criar README.md com a descrição do projeto
cat <<EOF > README.md
# 📌 Relatório do Laboratório BGP 101

## 📖 Introdução

Concluí o **laboratório final** do curso **BGP 101: O Curso Mais Completo sobre Border Gateway Protocol (BGP)** na **Leonardo Furtado Academy**. Este foi um desafio prático que consolidou meus conhecimentos sobre **BGP**, abordando **filtros de anúncio, segurança, engenharia de tráfego e VPNs**.

---

## 🌐 Descrição da Topologia

O ambiente simula uma rede complexa com **múltiplos Sistemas Autônomos (ASs)** interconectados, refletindo um cenário realista de operação BGP.

- **AS11**: Cliente do **AS1**, contrata trânsito IP para fornecer internet aos assinantes.
- **AS1**: Conectado ao **AS2**, estabelecendo uma relação de trânsito IP.
- **AS2**:
  - Core da rede com **Route Reflectors (R2 e R3)**.
  - Cliente do **AS4** e **AS5** para trânsito global.
  - Fornece backbone para o **AS65000**, que tem dois sites interligados via **VPNv4/VPNv6** e também acessa a internet.
- **AS3**: Cliente do **AS2**, com um cliente direto **AS31**.

---

## ⚙️ Etapas de Configuração

1. **🔧 Configuração Inicial**  
   - Definição de hostnames, senhas, interfaces e loopbacks para **IPv4** e **IPv6**.

2. **📡 OSPFv3 no AS2**  
   - Transporte do IBGP e recursividade do **NEXT_HOP**, otimizando a topologia.

3. **🔁 IBGP no AS2**  
   - Configuração de **Route Reflectors**, communities e **NEXT_HOP self**.

4. **🌍 EBGP entre ASs**  
   - Estabelecimento de peering e propagação de communities entre ASs.

5. **📢 Anúncio de Rotas**  
   - Redistribuição de prefixos com **route-maps** e **prefix-lists**.

6. **🚦 Filtros de Anúncio**  
   - Prevenção de **route leaks**, filtragem de prefixos bogon e definição de **LOCAL_PREF**.

7. **🚀 Engenharia de Tráfego**  
   - Configuração de **políticas BGP**, incluindo **RTBH** para mitigação de **DDoS**.

8. **🔒 Segurança**  
   - Implementação de **MD5**, **GTSM**, **uRPF strict mode** e **CoPP**.

9. **🏆 BGP VPNv4/VPNv6**  
   - Configuração de **MPLS e MP-BGP** para interligar os sites do **AS65000**.

---

## 🔗 Configurações e Resultados

As configurações completas e as saídas dos roteadores estão disponíveis no meu repositório.

---

## ✅ Conclusão

O **laboratório foi concluído com sucesso**, implementando todas as configurações necessárias para garantir **funcionalidade, segurança e eficiência** da rede. A topologia complexa permitiu testar cenários reais de **roteamento, engenharia de tráfego e VPNs**. 💪
EOF

# Criar a pasta imagens e copiar as imagens do laboratório
mkdir imagens
cp -r "C:\Users\Danilo\Desktop\BGP101"/* ./imagens/

# Adicionar todos os arquivos ao Git
git add .

# Fazer commit
git commit -m "Adicionando descrição e imagens do Laboratório BGP 101"

# Criar repositório no GitHub via API (requer token de autenticação)
curl -u "$GITHUB_USER" https://api.github.com/user/repos -d "{\"name\":\"$REPO\"}"

# Adicionar repositório remoto e enviar os arquivos
git branch -M main
git remote add origin "https://github.com/$GITHUB_USER/$REPO.git"
git push -u origin main




