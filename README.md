# 🧠 Desafio DIO - Azure Virtual Machines

Este projeto faz parte do desafio da **Digital Innovation One (DIO)** sobre máquinas virtuais na **Azure**.  
O objetivo é criar uma VM Windows no Azure Portal e documentar o processo.

---

## 🚀 Objetivo do Projeto
- Criar uma máquina virtual Windows no Azure.  
- Configurar rede e credenciais de acesso.  
- Conectar via RDP e validar funcionamento.  

---

## 🧱 Passo a Passo

1. Acesse o [Portal do Azure](https://portal.azure.com).  
2. Clique em **Criar um recurso** → **Máquina Virtual**.  
3. Configure:
   - Nome da VM: `VM-Windows-DIO`  
   - Região: `West US 2` 
   - Imagem: `Windows Server 2022 Datacenter: Azure Edition - Gen2`  
   - Tamanho: `tandard D2als v7 (2 vcpus, 4 GiB memória)`  
   - Usuário/Admin: `vitorgsf`  
   - Senha: `*************`  
4. Configure a rede permitindo **RDP (porta 3389)**.  
5. Clique em **Revisar + Criar** e aguarde a implantação.  
6. Conecte-se via **Remote Desktop** usando o IP público da VM.  

---

## 📊 Resultado Esperado
- VM criada e acessível via RDP.  
- Ambiente Windows Server pronto para testes.  
- Capturas de tela adicionadas na pasta `/images`.  

---

## 🧾 Entrega do Desafio
- Repositório público no GitHub com:  
  - `README.md` detalhado (este arquivo)  
  - Pasta `/images` com prints da criação e conexão da VM  

---
