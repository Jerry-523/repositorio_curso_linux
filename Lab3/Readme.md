# Laboratório — Sessão 3 
## Hardening de Redes Linux e Configuração de Firewalls
---
### Passo 1

**Exercicio 1** Verificar o `status` atual do UFW:

<img width="648" height="328" alt="image" src="https://github.com/user-attachments/assets/ed1e9986-41b0-48b7-984d-5ea15ead6037" />

Usei o comando `sudo ufw status` para fazer a verificacao do estado da firewall

---
**Exercicio 1** Verificar o `status` atual do UFW:

```
root@ubuntu:~$ ufw status
Status: inactive
root@ubuntu:~$ ufw enable
Firewall is active and enabled on system startup
root@ubuntu:~$ ufw status
Status: active
root@ubuntu:~$ 
```

Usei o comando `sudo ufw status` para fazer a verificacao do estado da firewall

---

### Passo 2

**Exercicio 2** Alterar as políticas padrão — **bloquear entrada, permitir saída:**

<img width="648" height="328" alt="image" src="https://github.com/user-attachments/assets/aadfead8-52b1-474c-b68a-f7e3778fd4bc" />

Usei configuracao padrao de seguranca bloqueando por padrao as requisicoes de entradas e permitindo apenas as requisicoes de saida

---

### Criterio 2
<img width="855" height="866" alt="image" src="https://github.com/user-attachments/assets/e76b6ec4-ce46-4919-95a0-961b12e1bb01" />
