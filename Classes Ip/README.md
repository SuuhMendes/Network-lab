# 🌐 Guia Prático: Classes de Endereços IP (IPv4)

<p align="center">
  <img src="https://img.shields.io/badge/Redes-IPv4-00bceb?style=for-the-badge&logo=cisco&logoColor=white" alt="IPv4"/>
  <img src="https://img.shields.io/badge/Status-Estudo_&_Prática-D946EF?style=for-the-badge" alt="Status"/>
</p>

## 🎯 O que é um Endereço IP?
O termo **IP** significa *Internet Protocol*. Um endereço IP identifica dispositivos em uma rede, permitindo a comunicação entre eles.

Um endereço **IPv4** possui **32 bits**, divididos em **4 partes (octetos)**, com valores que variam de **0 a 255**. 
* *Exemplo:* `192.168.1.10`

  ---

## 🚀 Uma Visão Geral sobre o IPv6
Devido ao esgotamento dos endereços IPv4, o **IPv6** (Internet Protocol version 6) foi desenvolvido para suprir a demanda mundial por novos endereços de dispositivos conectados.

* **Tamanho:** Possui **128 bits** (contra 32 bits do IPv4), o que gera uma quantidade praticamente infinita de endereços disponíveis.
* **Formato:** Utiliza representação **hexadecimal** dividida em 8 blocos separados por dois-pontos (`:`).
* *Exemplo:* `2001:0db8:85a3:0000:0000:8a2e:0370:7334`
* **Vantagens Principais:** Segurança integrada nativamente (IPsec), melhor roteamento e eliminação da necessidade de NAT (Network Address Translation) em grande escala.

---

## 📊 As Três Principais Classes de IP

### 🅰️ Classe A
Indicada para redes muito grandes, com grande quantidade de dispositivos.
* **Primeiro octeto:** 1 a 126
* **Máscara padrão:** `255.0.0.0` (Prefixo `/8`)
* **Uso principal:** Grandes corporações e governos
* *Exemplo:* `10.0.0.1`

### 🅱️ Classe B
Indicada para redes de tamanho médio.
* **Primeiro octeto:** 128 a 191
* **Máscara padrão:** `255.255.0.0` (Prefixo `/16`)
* **Capacidade:** Até 65.534 hosts por rede
* **Uso principal:** Universidades e médias empresas
* *Exemplo:* `172.16.0.1`

### 🅲 Classe C
Indicada para redes menores, como redes locais, residências e escritórios.
* **Primeiro octeto:** 192 a 223
* **Máscara padrão:** `255.255.255.0` (Prefixo `/24`)
* **Capacidade:** Até 254 hosts por rede
* **Uso principal:** Redes residenciais e escritórios
* *Exemplo:* `192.168.1.1`

---

## 📋 Tabela Comparativa Geral

| Classe | Faixa Inicial | Máscara Padrão | Uso Principal |
| :--- | :--- | :--- | :--- |
| **Classe A** | 1 a 127 | `255.0.0.0` | Grandes corporações e governos |
| **Classe B** | 128 a 191 | `255.255.0.0` | Universidades e médias empresas |
| **Classe C** | 192 a 223 | `255.255.255.0` | Redes residenciais e escritórios |

---

## 💡 Conclusão
Compreender a divisão entre as Classes A, B e C é o primeiro passo fundamental para projetar redes eficientes e seguras, seja simulando topologias no *Cisco Packet Tracer* ou estruturando ambientes reais.
