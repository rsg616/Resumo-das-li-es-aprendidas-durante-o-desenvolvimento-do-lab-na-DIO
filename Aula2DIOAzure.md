# Resumo sobre Criação de Máquina Virtual no Microsoft Azure

## Introdução

Durante este laboratório da DIO, aprendi como criar e configurar uma máquina virtual (VM) na plataforma **Microsoft Azure**, além de entender melhor como funciona o uso de serviços em nuvem. Esta documentação serve como material de apoio para futuras implementações e revisões.

---

## Principais Conceitos Aprendidos

- **O que é uma Máquina Virtual (VM):**
  Uma máquina virtual é uma emulação de um computador físico que roda em um ambiente de nuvem. Ela pode ter seu próprio sistema operacional, aplicativos e configurações.

- **Vantagens de Usar o Azure:**
  - Alta disponibilidade
  - Escalabilidade rápida
  - Segurança integrada
  - Economia de custos (paga apenas pelo que usa)

- **Criação de uma VM no Azure:**
  1. Acessar o portal do Azure: [https://portal.azure.com](https://portal.azure.com)
  2. Clicar em "Máquinas Virtuais" e depois em "Adicionar".
  3. Preencher os dados básicos:
     - **Nome da VM**
     - **Sistema Operacional** (Windows Server ou Linux)
     - **Tamanho da máquina** (quantidade de CPU/RAM)
     - **Usuário e senha** para acesso.
  4. Configurar opções de rede e armazenamento.
  5. Revisar e criar.

- **Acesso Remoto à VM:**
  - Para Windows: Utilizar o **Remote Desktop Protocol (RDP)**.
  - Para Linux: Utilizar **SSH** via terminal.

- **Boas Práticas:**
  - Sempre usar recursos em regiões próximas ao seu público/usuário final.
  - Criar regras de firewall seguras (permitir apenas IPs necessários).
  - Desligar a VM quando não estiver em uso para economizar créditos.

---

## Dicas Úteis

- Utilize o **Azure Quickstart Templates** para acelerar a criação de ambientes padronizados.
- Monitore os recursos com **Azure Monitor** para evitar gastos desnecessários.
- Faça **backups regulares** das máquinas virtuais críticas.
- Use **tags** nos recursos para organização e controle de custos.

---

## Capturas de Tela (Opcional)

> Se você quiser, pode criar uma pasta `/images` no repositório e colocar prints de tela como:
> - Tela de criação da VM
> - Configurações da máquina
> - Exemplo de conexão via RDP ou SSH

---

## Conclusão

Este laboratório foi essencial para aplicar na prática os conceitos de computação em nuvem e iniciar o trabalho com o Microsoft Azure. O aprendizado de criar, configurar e gerenciar máquinas virtuais é uma habilidade fundamental para quem deseja trabalhar com cloud computing.

---

