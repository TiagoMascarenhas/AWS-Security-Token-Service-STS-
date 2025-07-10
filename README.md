# 🔐 AWS STS - Uso de Credenciais Temporárias com IAM e Python

Este projeto foi desenvolvido como parte dos laboratórios da **Escola da Nuvem** e demonstra o uso do **AWS Security Token Service (STS)** para gerar e utilizar credenciais temporárias a partir de uma role IAM, com automação via script Python no AWS CloudShell.

---

## 🎯 Objetivo

- Criar uma role temporária com permissões ao Amazon S3.
- Configurar política de confiança personalizada.
- Gerar credenciais temporárias via **STS** usando **Python + boto3**.
- Testar acesso autorizado e acesso negado com base nas permissões da role.
- Simular expiração de sessão e invalidar as credenciais.
- Alterar a política de confiança e validar impacto na autorização.

---

## 🧰 Tecnologias e Serviços Utilizados

- **AWS IAM**
- **AWS STS**
- **Amazon S3**
- **AWS CLI**
- **AWS CloudShell**
- **Python 3**
- **boto3**

---

## 📌 Etapas Realizadas

1. Configuração do ambiente com Python e boto3 no AWS CloudShell.
2. Criação de uma role com política `AmazonS3FullAccess`.
3. Aplicação de política de confiança personalizada para um usuário IAM.
4. Alternância para a role via console e CLI.
5. Geração de credenciais temporárias com script Python.
6. Configuração da AWS CLI com essas credenciais.
7. Validação de acesso ao S3 (permitido) e ao Lambda (negado).
8. Simulação de expiração de sessão.
9. Edição da política de confiança para negar novo acesso.
10. Limpeza dos recursos utilizados.


---![WhatsApp Image 2025-06-09 at 17 50 25 (1)](https://github.com/user-attachments/assets/5a09a8a6-e293-43fe-83d5-29f58c6db16d)


## 📎 Resultados

✅ Acesso autorizado ao S3 com credenciais temporárias  
❌ Acesso negado ao Lambda conforme política restrita  
⚠️ Erro de credencial expirada após o tempo de sessão (1 hora)  
🔒 Acesso bloqueado após alteração da política de confiança

---

## 🤝 Contato

- GitHub: [https://github.com/seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [https://www.linkedin.com/in/tiagomascarenhas/](https://www.linkedin.com/in/tiagomascarenhas/)

