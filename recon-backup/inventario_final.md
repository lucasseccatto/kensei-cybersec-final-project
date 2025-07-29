# Inventário Final de Ativos

## Rede Corporativa (corp_net - 10.10.10.0/24)

---

**IP:** `10.10.10.1`
**Hostname:** N/A
**SO estimado:** Linux
**Portas abertas:** `111/tcp`, `51393/tcp`
**Serviços:** `rpcbind`, `unknown`

---

**IP:** `10.10.10.10`
**Hostname:** `WS_001.projeto_final_opcao_1_corp_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.10.101`
**Hostname:** `WS_002.projeto_final_opcao_1_corp_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.10.127`
**Hostname:** `WS_003.projeto_final_opcao_1_corp_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.10.222`
**Hostname:** `WS_004.projeto_final_opcao_1_corp_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

## Rede de Infraestrutura (infra_net - 10.10.30.0/24)

---

**IP:** `10.10.30.1`
**Hostname:** N/A
**SO estimado:** Linux
**Portas abertas:** `111/tcp`, `51393/tcp`
**Serviços:** `rpcbind`, `unknown`

---

**IP:** `10.10.30.10`
**Hostname:** `ftp-server.projeto_final_opcao_1_infra_net`
**SO estimado:** Linux
**Portas abertas:** `21/tcp`
**Serviços:** `ftp`
**Notas:** Falha visível: O protocolo FTP transmite credenciais e dados em texto claro.

---

**IP:** `10.10.30.11`
**Hostname:** `mysql-server.projeto_final_opcao_1_infra_net`
**SO estimado:** Linux
**Portas abertas:** `3306/tcp`, `33060/tcp`
**Serviços:** `mysql`, `mysqlx`
**Notas:** Dados sensíveis: Servidor de banco de dados (MySQL versão `8.0.43`).

---

**IP:** `10.10.30.15`
**Hostname:** `samba-server.projeto_final_opcao_1_infra_net`
**SO estimado:** Linux
**Portas abertas:** `139/tcp`, `445/tcp`
**Serviços:** `netbios-ssn`, `microsoft-ds` (Samba)
**Notas:** Dados sensíveis: Potencial para dados sensíveis em compartilhamentos de arquivos.

---

**IP:** `10.10.30.17`
**Hostname:** `openldap.projeto_final_opcao_1_infra_net`
**SO estimado:** Linux
**Portas abertas:** `389/tcp`, `636/tcp`
**Serviços:** `ldap`, `ldapssl`
**Notas:** Dados sensíveis: Servidor de diretório. Divulgação de informação de configuração (`namingContexts: dc=example,dc=org`).

---

**IP:** `10.10.30.117`
**Hostname:** `zabbix-server.projeto_final_opcao_1_infra_net`
**SO estimado:** Linux
**Portas abertas:** `80/tcp`, `10051/tcp`, `10052/tcp`
**Serviços:** `http` (Nginx), `zabbix-trapper`, `unknown`
**Notas:** Dados sensíveis: Plataforma de monitoramento (Zabbix). Falha visível: Software desatualizado (PHP `7.3.14`).

---

**IP:** `10.10.30.227`
**Hostname:** `legacy-server.projeto_final_opcao_1_infra_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A
**Notas:** O hostname "legacy-server" sugere um sistema legado, que pode estar desatualizado e vulnerável.

---

## Rede de Visitantes (guest_net - 10.10.50.0/24)

---

**IP:** `10.10.50.1`
**Hostname:** N/A
**SO estimado:** Linux
**Portas abertas:** `111/tcp`, `51393/tcp`
**Serviços:** `rpcbind`, `unknown`

---

**IP:** `10.10.50.2`
**Hostname:** `laptop-vastro.projeto_final_opcao_1_guest_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.50.3`
**Hostname:** `macbook-aline.projeto_final_opcao_1_guest_net`
**SO estimado:** macOS (baseado no hostname)
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.50.4`
**Hostname:** `notebook-carlos.projeto_final_opcao_1_guest_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

---

**IP:** `10.10.50.5`
**Hostname:** `laptop-luiz.projeto_final_opcao_1_guest_net`
**SO estimado:** Desconhecido
**Portas abertas:** Nenhuma porta aberta encontrada.
**Serviços:** N/A

## Corp_net (10.10.10.0/24)

### Host 1
- **IP:** 10.10.10.1
- **Hostname:** (não identificado)
- **SO estimado:** —
- **Portas abertas:** 111/tcp, 51393/tcp
- **Serviços:** rpcbind, unknown
- **Notas:** Provável gateway da rede

### Host 2
- **IP:** 10.10.10.10
- **Hostname:** WS_001
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Estação de trabalho

### Host 3
- **IP:** 10.10.10.101
- **Hostname:** WS_002
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Estação de trabalho

### Host 4
- **IP:** 10.10.10.127
- **Hostname:** WS_003
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Estação de trabalho

### Host 5
- **IP:** 10.10.10.222
- **Hostname:** WS_004
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Estação de trabalho

### Host 6
- **IP:** 10.10.10.2
- **Hostname:** f66639f5f3f4 (Kali)
- **SO estimado:** Linux
- **Portas abertas:** 47802/tcp
- **Serviços:** Porta dinâmica
- **Notas:** Host do analista, sem relevância de risco

## Guest_net (10.10.50.0/24)

### Host 1
- **IP:** 10.10.50.1
- **Hostname:** (não identificado)
- **SO estimado:** —
- **Portas abertas:** 111/tcp, 51393/tcp
- **Serviços:** rpcbind, unknown
- **Notas:** Provável gateway da rede

### Host 2
- **IP:** 10.10.50.2
- **Hostname:** laptop-vastro
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Dispositivo de visitante

### Host 3
- **IP:** 10.10.50.3
- **Hostname:** macbook-aline
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Dispositivo de visitante

### Host 4
- **IP:** 10.10.50.4
- **Hostname:** notebook-carlos
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Dispositivo de visitante

### Host 5
- **IP:** 10.10.50.5
- **Hostname:** laptop-luiz
- **SO estimado:** —
- **Portas abertas:** Nenhuma
- **Serviços:** —
- **Notas:** Dispositivo de visitante

### Host 6
- **IP:** 10.10.50.6
- **Hostname:** f66639f5f3f4 (Kali)
- **SO estimado:** Linux
- **Portas abertas:** 48956/tcp
- **Serviços:** Porta dinâmica
- **Notas:** Host do analista, sem relevância de risco