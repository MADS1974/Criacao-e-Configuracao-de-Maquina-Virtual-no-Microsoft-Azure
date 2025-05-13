# ☁️ Desafio: Criação e Configuração de Máquina Virtual no Microsoft Azure

Este repositório foi criado como parte do desafio proposto pela DIO, com o objetivo de praticar a criação e configuração de uma máquina virtual na plataforma **Microsoft Azure**. Aqui você encontrará resumos, anotações e dicas sobre o uso do Azure, servindo como material de apoio para estudos e futuras implementações.

## 📝 Descrição

Nesse projeto, você irá descobrir como a nuvem pode melhorar a eficiência e escalabilidade. Este desafio é voltado para profissionais e entusiastas que desejam explorar conceitos básicos de **Azure** e **Full-Stack**, com foco em práticas essenciais para iniciantes.

**Nível:** Básico  
**Especialista:** Valéria Baptista  
**Cargo:** Head of Cloud and Cybersecurity, CloudData Tech & DevOps  
[LinkedIn](https://www.linkedin.com/in/valeria-baptista)

## 🚀 Objetivos do Desafio

- **Aplicar conceitos aprendidos** em um ambiente prático.
- **Documentar processos técnicos** de forma clara e estruturada.
- **Utilizar o GitHub** como ferramenta para compartilhamento de documentação técnica.

## 📋 Requisitos do Desafio

Para concluir este desafio, você deverá:

1. **Assistir a todas as vídeo-aulas**:
   - Não pule nenhuma etapa! As aulas contêm informações essenciais para o sucesso do seu projeto.

2. **Criar um repositório público no GitHub** contendo:
   - Um arquivo `README.md` detalhado.
   - Quaisquer arquivos adicionais que sejam relevantes para documentar sua experiência.
   - Opcionalmente, capturas de tela relevantes organizadas em uma pasta.

3. **Enviar o link do repositório** e uma breve descrição clicando no botão “Entregar Projeto”.

## 🎯 Estrutura do Repositório

- **README.md**: Este arquivo contém a documentação principal do desafio.
- **/screenshots**: Pasta opcional para armazenar capturas de tela relevantes.
- **/notes**: Arquivos adicionais com resumos e anotações sobre o uso do Azure.

## 🖥️ Passos para Realizar o Desafio

1. **Criar uma Máquina Virtual no Azure**:
   - Siga o guia oficial: [Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal).

2. **Documentando o Processo**:

- **Etapa 1: Acessar o Portal do Azure**  
     Acesse o [Portal do Azure](https://portal.azure.com/) com sua conta Microsoft. Certifique-se de que você possui uma assinatura ativa para criar recursos.

- **Etapa 2: Criar um Recurso**  
     No menu lateral, clique em **"Criar um recurso"** e selecione **"Máquina Virtual"** na categoria de **Computação**.

- **Etapa 3: Configurar a Máquina Virtual**  
     Preencha os campos obrigatórios:  
  - **Assinatura**: Escolha a assinatura ativa.  
    - **Grupo de Recursos**: Crie um novo grupo ou selecione um existente.  
    - **Nome da Máquina Virtual**: Defina um nome descritivo, como `VM-Teste`.  
    - **Região**: Escolha a região mais próxima para reduzir a latência.  
    - **Imagem**: Selecione o sistema operacional desejado, como **Windows Server 2022** ou **Ubuntu 20.04 LTS**.  
    - **Tamanho**: Escolha o tamanho da máquina virtual com base nos requisitos de CPU e memória.  

- **Etapa 4: Configurar a Rede**  
     Configure a rede virtual e o grupo de segurança de rede (NSG). Certifique-se de permitir portas necessárias, como **RDP (3389)** para Windows ou **SSH (22)** para Linux.

- **Etapa 5: Revisar e Criar**  
     Revise todas as configurações e clique em **"Criar"**. Aguarde a implantação ser concluída.

- **Etapa 6: Conectar à Máquina Virtual**  
     Após a implantação, acesse a máquina virtual:  
- Para Windows: Baixe o arquivo RDP e conecte-se usando as credenciais configuradas.  
  - Para Linux: Use um cliente SSH para acessar a máquina virtual.

- **Dicas e Observações**:  
  - Sempre escolha a região mais próxima para reduzir custos e melhorar o desempenho.  
  - Utilize **tags** para organizar e identificar recursos facilmente.  
  - Configure alertas de monitoramento para acompanhar o uso e os custos da máquina virtual.  
  - Após o uso, desligue ou exclua a máquina virtual para evitar cobranças desnecessárias.

## 🌐 Interface do Portal do Microsoft Azure

A interface do portal do Microsoft Azure oferece uma visão centralizada de todos os serviços disponíveis. Na seção "Todos os serviços", é possível explorar categorias como **IA + Machine Learning**, **Computação**, **Contêineres**, **Bancos de dados**, entre outras. Além disso, serviços populares como **Máquinas virtuais**, **Grupos de recursos**, **Serviços de Aplicativos** e **Bancos de dados SQL** estão facilmente acessíveis, permitindo o gerenciamento eficiente de recursos na nuvem.

## 📊 Entendendo o SLA no Azure

A tabela abaixo apresenta os níveis de SLA (Service Level Agreement) oferecidos pelo Azure e o tempo máximo de inatividade permitido para cada nível. O SLA é um compromisso de disponibilidade do serviço, sendo um fator crucial para garantir a confiabilidade das aplicações hospedadas na nuvem.

| **SLA**   | **Tempo de inatividade por semana** | **Tempo de inatividade por mês** | **Tempo de inatividade por ano** |
|-----------|------------------------------------|----------------------------------|----------------------------------|
| 99%       | 1,68 hora                          | 7,2 horas                       | 3,65 dias                       |
| 99,9%     | 10,1 minutos                       | 43,2 minutos                    | 8,76 horas                      |
| 99,95%    | 5 minutos                          | 21,6 minutos                    | 4,38 horas                      |
| 99,99%    | 1,01 minuto                        | 4,32 minutos                    | 52,56 minutos                   |
| 99,999%   | 6 segundos                         | 25,9 segundos                   | 5,26 minutos                    |

### Explicação

- **SLA (Service Level Agreement)**: Representa o percentual de tempo em que o serviço estará disponível.
- **Tempo de inatividade**: Indica o tempo máximo que o serviço pode ficar indisponível dentro de um período específico (semana, mês ou ano).
- Quanto maior o SLA, menor o tempo de inatividade permitido, garantindo maior confiabilidade para aplicações críticas.

## 📚 Recursos Úteis

- **Documentações Oficiais**:
  - [Início Rápido: Criar uma máquina virtual do Windows no Portal do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal).

- **Materiais Complementares sobre GitHub**:
  - [GitHub Quick Start](https://github.com/github/quickstart).
  - [GitBook: Formação GitHub Certification](https://git-scm.com/book/en/v2).
  - [Documentação do GitHub](https://docs.github.com/).
  - [GitHub Markdown](https://guides.github.com/features/mastering-markdown/).

## ✅ Toda implementação deste código foi feita seguindo boas práticas de programação orientada a objetos e seguindo as orientações do Expert <www.dio.me>

### Follow me

- [MARCIO ADRIANO DA SILVA | LinkedIn](https://www.linkedin.com/in/mads1974/)
