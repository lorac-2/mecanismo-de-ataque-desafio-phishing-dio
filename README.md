

# 🛡️ mecanismo-phishing-de-ataque-desafio-dio


## 🚀 Status do Projeto

![Concluído](https://img.shields.io/badge/Status-Concluído-success)  
![DIO](https://dio.me)  
![Formação](https://img.shields.io/badge/Formação-Cybersecurity%20Especialist-darkgreen)

---

## 📝 Descrição do Desafio

Este projeto foi desenvolvido como parte da **Formação em Cybersecurity Specialist da DIO** e tem como objetivo a **demonstração prática e educacional** da técnica de **Phishing (Engenharia Social)** utilizando a ferramenta **Social-Engineer Toolkit (SEToolkit)** no Kali Linux.

O foco é entender o **mecanismo de ataque de *credential harvesting*** (captura de credenciais) para reforçar as estratégias de **defesa e mitigação** contra esse tipo de ameaça, que é uma das mais comuns na cibersegurança.

**O cenário simulado consistiu na criação de uma página falsa de login do Facebook para fins de demonstração.**

### 💡 Objetivos de Aprendizagem

- **Compreender** o ciclo de vida de um ataque de *phishing*.  
- **Aplicar** o SEToolkit em um ambiente controlado e ético.  
- **Documentar** o raciocínio técnico e as etapas de execução de forma clara.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Kali Linux:** Sistema operacional para testes de penetração e segurança.  
- **Social-Engineer Toolkit (SEToolkit):** Ferramenta de engenharia social.  
- **Terminal / Bash:** Execução de comandos.  
- **GitHub / Markdown:** Versionamento e documentação.

---

## 🪜 Passos de Execução (Modo Demonstração)

Abaixo estão as 11 etapas seguidas para a execução do desafio, com os comandos e os prints correspondentes.

--- 

### 1. Inicialização do SEToolkit

**Comando no Terminal:**

```bash
sudo su
# digite a senha: kali
setoolkit
```


---

### 2. Seleção de Engenharia Social

**Opção Selecionada:**

```
1) Social-Engineering Attacks
```


---

### 3. Seleção do Vetor de Ataque

**Opção Selecionada:**

```
2) Website Attack Vectors
```



---

### 4. Seleção do Método de Credenciais

**Opção Selecionada:**

```
3) Credential Harvester Attack Method
```



### 5. Seleção do Tipo de Clonagem

**Opção Selecionada:**

```
2) Site Cloner
```


---

### 6. Definição do IP do Atacante

**Comando Implícito:**  
O SEToolkit geralmente insere automaticamente o IP local.


---

### 7. Inserção da URL Alvo

**Informação Inserida:**

```
https://www.facebook.com
```


---

### 8. Confirmação do Clone (Fase 1)

**Comando Implícito:**  
Confirmação de que a página foi clonada.


---

### 9. Confirmação do Clone (Fase 2)

**Comando Implícito:**  
Script de Credential Harvester inicializado.

---

### 10. Servidor em Espera (Listening)

**Comando Implícito:**  
Servidor rodando e aguardando submissão de credenciais.



---

### 11. Captura de Credenciais

**Resultado no Terminal:**  
Exibição das credenciais capturadas (Login e Senha).


---

## 🛑 Aviso Legal (Disclaimer)

Este projeto é estritamente para fins educacionais, de estudo e demonstração de conceitos de cibersegurança.

O uso das técnicas e ferramentas demonstradas para atacar, comprometer ou obter acesso não autorizado a sistemas, redes ou informações de terceiros é ilegal e antiético.

O objetivo deste desafio é fortalecer a postura de defesa, ajudando a identificar e mitigar as ameaças de phishing no mundo real.

---

## 🧑‍💻 Autor

**Nome:** Carolina Rego  
**GitHub:** [@lorac-2](https://github.com/lorac-2)  
**LinkedIn:** [carolinabrazv](https://www.linkedin.com/in/carolinabrazv)

---

Feito com ❤️ por lorac-2 

---
