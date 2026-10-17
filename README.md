# 🛡️ DDoS-Ripper

### Ferramenta de estudo sobre ataques DDoS e segurança de redes

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Platform](https://img.shields.io/badge/Plataformas-Linux%20%7C%20Windows%20%7C%20macOS%20%7C%20Android-green)
![Education](https://img.shields.io/badge/Finalidade-Educacional-orange)
![Security](https://img.shields.io/badge/Segurança-Cibernética-red)

> [!IMPORTANT]
> **PROJETO DESTINADO EXCLUSIVAMENTE A FINS EDUCACIONAIS E DE PESQUISA.**
>
> A utilização desta ferramenta deve ocorrer somente em ambientes controlados, laboratórios acadêmicos ou infraestruturas próprias, com autorização expressa dos responsáveis.
>
> O uso não autorizado contra servidores, redes ou serviços de terceiros pode constituir infração civil ou criminal.

---

## 📖 Sobre o projeto

O **DDoS-Ripper** é um projeto desenvolvido em Python para o estudo de conceitos relacionados à Negação de Serviço Distribuída (*Distributed Denial of Service — DDoS*).

Seu objetivo educacional é auxiliar estudantes, professores e pesquisadores a compreender o funcionamento de ameaças à disponibilidade de sistemas computacionais e os mecanismos de proteção utilizados em redes.

![dddd](https://user-images.githubusercontent.com/49250151/96265488-57e53d00-0f7a-11eb-8936-ce2e9a2c42cd.PNG)

### 🎯 Objetivos educacionais

- Compreender o conceito e o funcionamento de ataques DDoS.
- Estudar protocolos e comunicação em redes.
- Identificar vulnerabilidades relacionadas à disponibilidade.
- Conhecer estratégias de monitoramento e mitigação.
- Desenvolver conhecimentos em segurança cibernética.
- Promover o uso ético e responsável das ferramentas de segurança.

---

## 🌐 O que é um ataque DDoS?

Um ataque de **Negação de Serviço Distribuída (DDoS)** ocorre quando múltiplas fontes enviam grandes quantidades de tráfego ou requisições para um servidor, serviço ou infraestrutura de rede, buscando comprometer sua disponibilidade.

Esses ataques podem envolver computadores, servidores e dispositivos de Internet das Coisas (IoT), inclusive equipamentos comprometidos por softwares maliciosos.

### 🚗 Exemplo prático

Imagine uma rodovia que recebe um número excessivo de veículos simultaneamente.

O congestionamento impede que os motoristas cheguem normalmente aos seus destinos.

De maneira semelhante, um ataque DDoS pode sobrecarregar os recursos de um servidor, dificultando ou impedindo o acesso dos usuários legítimos.

---

## 💻 Sistemas compatíveis

| Sistema operacional | Ambiente |
|---|---|
| 🐧 Linux | Ubuntu, Debian, Kali Linux |
| 🪟 Windows | Prompt de Comando, PowerShell |
| 🍎 macOS | Terminal |
| 📱 Android | Termux |

> [!NOTE]
> A compatibilidade depende da versão do Python, das bibliotecas utilizadas e das características do sistema operacional.

---

## ⚙️ Pré-requisitos

Antes de iniciar os estudos, recomenda-se instalar:

- [Python 3](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- Editor de código, como [Visual Studio Code](https://code.visualstudio.com/)
- Ambiente virtual ou laboratório de redes para testes autorizados.

### 📱 Android — Termux

Instale as dependências:

```bash
pkg update && pkg upgrade -y
pkg install git -y
pkg install python -y
```

### 🐧 Linux — Debian, Ubuntu e derivados

Atualize os repositórios e instale as dependências:

```bash
sudo apt update
sudo apt install git python3 -y
```

### 🪟 Windows

Instale o Python 3 e o Git por meio dos respectivos sites oficiais.

Verifique a instalação:

```bash
python --version
git --version
```

### 🍎 macOS

Instale o Python 3 e o Git.

Caso utilize o Homebrew:

```bash
brew install python git
```

---

## 📂 Obtendo o código-fonte

O repositório de referência está disponível em:

**https://github.com/profjvidal/DDoS-Ripper**

Para obter o código-fonte:

```bash
git clone https://github.com/profjvidal/DDoS-Ripper.git
```

Acesse o diretório:

```bash
cd DDoS-Ripper
```

Liste os arquivos:

**Linux, macOS ou Termux:**

```bash
ls
```

**Windows (Prompt de Comando):**

```cmd
dir
```

> [!CAUTION]
> A disponibilização do código-fonte não representa autorização para executar ataques ou testes de carga contra sistemas de terceiros. Antes de executar scripts desconhecidos, analise seu funcionamento e utilize ambientes isolados.

---

## 🧪 Aplicação em ambientes educacionais

O projeto pode ser utilizado como material complementar em disciplinas de:

| Disciplina | Aplicação |
|---|---|
| Redes de Computadores | Estudo de protocolos e tráfego |
| Segurança da Informação | Análise de ameaças e riscos |
| Administração de Redes | Monitoramento de infraestrutura |
| Sistemas Operacionais | Processos e comunicação |
| Programação em Python | Análise de código-fonte |
| Segurança Cibernética | Prevenção e mitigação de incidentes |

### Boas práticas para atividades práticas

1. Utilizar redes e equipamentos próprios ou autorizados.
2. Definir previamente o escopo dos testes.
3. Priorizar máquinas virtuais e ambientes isolados.
4. Monitorar o consumo de recursos.
5. Evitar qualquer impacto em serviços de terceiros.
6. Registrar os resultados para análise acadêmica.

Os parâmetros de execução capazes de produzir tráfego disruptivo devem ser estudados apenas em laboratório, sob supervisão e com limites de segurança definidos.

---

## ⚖️ Legislação brasileira aplicável

O uso de ferramentas de segurança cibernética deve observar a legislação vigente no Brasil.

### 📜 Lei nº 12.737/2012 — Lei Carolina Dieckmann

Introduziu dispositivos relacionados a crimes informáticos no Código Penal, incluindo o artigo 154-A, referente à invasão de dispositivo informático.

**Importante:** Um ataque DDoS não configura automaticamente o crime previsto no artigo 154-A. A tipificação depende das características da conduta.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2012/lei/l12737.htm)

### 📜 Lei nº 14.155/2021

Alterou dispositivos do Código Penal relacionados a crimes informáticos e fraudes eletrônicas.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14155.htm)

### 📜 Lei nº 12.965/2014 — Marco Civil da Internet

Estabelece princípios, garantias, direitos e deveres para o uso da Internet no Brasil.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l12965.htm)

### 📜 Lei nº 13.709/2018 — LGPD

A Lei Geral de Proteção de Dados Pessoais estabelece regras para o tratamento de dados pessoais, inclusive em meios digitais.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

### 📜 Decreto-Lei nº 2.848/1940 — Código Penal

O artigo 266 e outros dispositivos podem ser relevantes em situações que envolvam a interrupção ou perturbação de determinados serviços, conforme os requisitos legais de cada infração.

[Consultar Código Penal](https://www.planalto.gov.br/ccivil_03/decreto-lei/del2848compilado.htm)

> [!WARNING]
> **RESPONSABILIDADE LEGAL**
>
> A realização de ataques contra redes, servidores e serviços sem autorização pode gerar responsabilização civil e criminal.
>
> A alegação de finalidade educacional não afasta automaticamente a responsabilidade por eventuais atos ilícitos.

---

## 🔐 Ética e responsabilidade

Este projeto deve ser utilizado para aprendizado, pesquisa e conscientização sobre segurança da informação.

**Não utilize esta ferramenta para:**

- Atacar servidores públicos ou privados.
- Interromper serviços de terceiros.
- Realizar atividades de intimidação ou vingança.
- Comprometer a disponibilidade de sistemas.
- Executar testes sem autorização expressa.

**A segurança cibernética deve ser utilizada para proteger sistemas, prevenir incidentes e promover o uso responsável da tecnologia.**

---

## ⚠️ Isenção de responsabilidade

Este projeto é disponibilizado exclusivamente para fins educacionais e de pesquisa.

Os autores, colaboradores e mantenedores não autorizam sua utilização para atividades ilegais ou prejudiciais.

O usuário é responsável por cumprir a legislação aplicável, respeitar os direitos de terceiros e obter as autorizações necessárias.

Este aviso não afasta eventuais responsabilidades legalmente atribuíveis aos envolvidos.

---

## 👨‍💻 Créditos e colaboradores

### Projeto e desenvolvimento

Os créditos pelo desenvolvimento original e pelas contribuições ao código pertencem aos respectivos autores e colaboradores.

**Modificações atribuídas a:**

- [@palahsu](https://github.com/palahsu)

### Repositório de referência

- [profjvidal/DDoS-Ripper](https://github.com/profjvidal/DDoS-Ripper)

### Adaptação educacional

Tradução e organização do conteúdo para português brasileiro, com contextualização acadêmica, orientações éticas e referências à legislação brasileira.

### Comunidade e canais originalmente informados

[![GitHub](https://img.shields.io/badge/GitHub-palahsu-black?logo=github)](https://github.com/palahsu)

[![Telegram](https://img.shields.io/badge/Telegram-CyberClans-blue?logo=telegram)](https://t.me/CyberClans)

[![Facebook](https://img.shields.io/badge/Facebook-Perfil-blue?logo=facebook)](https://www.facebook.com/aduri.knox01/)

[![Telegram](https://img.shields.io/badge/Telegram-Contato-blue?logo=telegram)](https://t.me/AD0000000)

*Os canais acima foram preservados da documentação fornecida e podem não estar ativos.*

---

## 📄 Licença

Consulte o arquivo `LICENSE` do repositório original, caso disponível, para verificar as condições de utilização, modificação e redistribuição.

A finalidade educacional e a atribuição de créditos não substituem o cumprimento dos termos de licenciamento.

---

## 📚 Referências

- [Python — Documentação oficial](https://docs.python.org/3/)
- [OWASP — Open Worldwide Application Security Project](https://owasp.org/)
- [CERT.br — Centro de Estudos, Resposta e Tratamento de Incidentes de Segurança no Brasil](https://www.cert.br/)
- [NIC.br — Núcleo de Informação e Coordenação do Ponto BR](https://www.nic.br/)
- [Planalto — Legislação brasileira](https://www.planalto.gov.br/)

---

### 🎓 Segurança da informação é conhecimento, ética e responsabilidade.

**Estude para compreender. Pesquise para evoluir. Utilize o conhecimento para proteger.**

*Projeto apresentado para fins educacionais, acadêmicos e de pesquisa em segurança cibernética.*
