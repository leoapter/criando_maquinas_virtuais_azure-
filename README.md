# 🚀 Laboratório de Azure: Configuração de Máquina Virtual

## 📌 Visão Geral
Este repositório documenta o processo de criação e configuração de uma máquina virtual na plataforma **Microsoft Azure**. Ele serve como material de apoio para estudos e futuras implementações.

## 🎯 Objetivos
Ao explorar este repositório, você aprenderá a:
- Criar e configurar uma máquina virtual no Azure.
- Documentar processos técnicos de forma clara e estruturada.
- Utilizar o **GitHub** para compartilhamento de documentação técnica.

## 🛠️ Tecnologias Utilizadas
Este projeto utiliza os seguintes serviços e tecnologias:
- **Microsoft Azure** – Plataforma de computação em nuvem.
- **Azure Virtual Machines** – Serviço de máquinas virtuais.
- **Azure Networking** – Configuração de redes virtuais.
- **Azure Security** – Práticas recomendadas de segurança.
- **GitHub** – Plataforma para versionamento e compartilhamento de código.

## 📂 Estrutura do Repositório
````
/Azure-Lab
│── /VM-Setup
│   ├── README.md  (Guia de configuração da máquina virtual)
│   ├── vm-config.json  (Exemplo de configuração)
│── /Networking
│   ├── README.md  (Configuração de redes no Azure)
│   ├── vnet-diagram.png  (Diagrama de rede)
│── /Security
│   ├── README.md  (Práticas recomendadas de segurança)
│   ├── security-checklist.md  (Checklist de segurança)
│── /images
│   ├── vm-setup.png  (Captura de tela da configuração)
│   ├── network-settings.png  (Captura de tela das configurações de rede)
│── README.md  (Visão geral do projeto)
````

## 🚀 Como Criar uma Máquina Virtual no Azure
1. **Acesse o Portal do Azure** – Faça login em [portal.azure.com](https://portal.azure.com).
2. **Criação da Máquina Virtual**:
   - No menu lateral, selecione **Máquinas Virtuais**.
   - Clique em **Criar** > **Máquina Virtual**.
   - Escolha a **assinatura**, **grupo de recursos** e **região**.
   - Defina o **sistema operacional**, **tamanho da VM** e **credenciais de acesso**.
3. **Configuração de Rede**:
   - Configure a **rede virtual** e **sub-rede**.
   - Defina as **regras de segurança** para acesso remoto.
4. **Discos e Armazenamento**:
   - Escolha o tipo de disco (SSD Premium, SSD Standard, HDD).
   - Configure discos adicionais, se necessário.
5. **Revisão e Implantação**:
   - Revise todas as configurações e clique em **Criar**.
   - Aguarde a implantação e acesse a VM pelo **Azure Bastion** ou **RDP**.

## 🔹 Dicas e Melhores Práticas
- Utilize **tags** para organizar recursos no Azure.
- Habilite **backup automático** para maior segurança.
- Configure **alertas e monitoramento** via Azure Monitor.

## 📖 Glossário
- **VM (Virtual Machine)** – Máquina virtual criada no Azure.
- **VNet (Virtual Network)** – Rede virtual usada para conectar recursos no Azure.
- **NSG (Network Security Group)** – Grupo de segurança para controle de tráfego.
- **RDP (Remote Desktop Protocol)** – Protocolo para acesso remoto à VM.

## 📢 Avisos e Limitações
- Algumas configurações podem gerar custos adicionais no Azure.
- Certifique-se de revisar as políticas de segurança antes de expor serviços à internet.


## 🔗 Referências
- [Criar uma máquina virtual no Azure](https://learn.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops)
- [Práticas recomendadas para segurança de VMs](https://learn.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops)
- [Guia de Markdown no Azure DevOps](https://learn.microsoft.com/pt-br/azure/devops/project/wiki/markdown-guidance?view=azure-devops)

---
