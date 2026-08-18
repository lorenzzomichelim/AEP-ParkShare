# 🚗 ParkShare – Plataforma de Compartilhamento de Vagas de Estacionamento

> **AEP - 1ª Entrega (Bimestre 1)**  
> **Curso:** Engenharia de Software – UNICESUMAR  
> **Autores:** Lorenzzo Michelim Santos e Vinicius Meggiato  

---

## 📌 1. Sobre o Projeto
O **ParkShare** é uma solução baseada em economia compartilhada que conecta motoristas em busca de vagas de estacionamento a proprietários de garagens ou espaços ociosos. O projeto visa reduzir o tempo de circulação no trânsito urbano, otimizar o uso do espaço das cidades e monetizar espaços privados não utilizados.

### 🌿 Alinhamento com os ODS da ONU
O projeto está alinhado com o **ODS 11: Cidades e Comunidades Sustentáveis** (Metas 11.2 e 11.a), contribuindo para a redução de congestionamentos e da emissão de CO₂ nas áreas urbanas.

---

## 📋 2. Lista de Requisitos (Escopo)

1. O sistema deve permitir o cadastro de usuários com nome completo, CPF, e-mail, celular e perfil de acesso (Motorista ou Proprietário).
2. O sistema deve permitir que o proprietário cadastre suas vagas informando o endereço completo, tipo de veículo aceito, valor por hora e disponibilidade de horários.
3. O sistema deve permitir que o motorista pesquise e realize a reserva de uma vaga informando a data, horário de início e horário de término.
4. O sistema deve processar o pagamento da reserva pelo aplicativo, incluindo a opção de contratação de taxa de cobertura total para proteção do veículo.
5. O sistema deve permitir a assinatura de uma mensalidade para motoristas que desejam reservas ilimitadas de vagas durante o mês.
6. O sistema deve aplicar automaticamente uma taxa de multa financeira ao motorista caso o tempo estipulado da reserva seja violado.
7. O sistema deve permitir que motoristas e proprietários avaliem mutuamente a experiência após a conclusão do período de reserva.

---

## 📅 3. Cronograma de Execução

| Data Inicial | Data Final | Atividade | Responsável |
| :--- | :--- | :--- | :--- |
| 01/08/2026 | 05/08/2026 | Levantamento de Requisitos e Modelagem UML (Diagramas) | Lorenzzo Michelim |
| 06/08/2026 | 10/08/2026 | Criação do Banco de Dados MySQL e Script DER | Vinicius Meggiato |
| 11/08/2026 | 15/08/2026 | Estruturação da Arquitetura MVC e Classes Base em Java | Lorenzzo Michelim |
| 16/08/2026 | 20/08/2026 | Implementação do Módulo de Cadastro de Usuários e Vagas | Vinicius Meggiato |
| 21/08/2026 | 25/08/2026 | Implementação do Módulo de Reservas, Pagamentos e Regras de Multa | Lorenzzo Michelim |
| 26/08/2026 | 31/08/2026 | Testes do Sistema, Ajustes de Interface e Documentação Final | Vinicius Meggiato |

---

## 🛠️ 4. Justificativa Técnica e Arquitetura

- **Linguagem:** Java (Orientação a Objetos, tipagem forte e robustez).
- **Banco de Dados:** MySQL (Relacional, suporte a transações ACID para pagamentos e reservas).
- **Padrão Arquitetural:** MVC (*Model-View-Controller*) para desacoplamento de código e organização das camadas de interface, lógica e persistência.

---

## 📁 5. Estrutura do Repositório

```text
ParkShare/
├── /docs
│   ├── Diagrama_Classe_ParkShare.png
│   ├── DER_ParkShare.png
│   └── Entrega_Bimestre_1.pdf
├── /database
│   ├── script_banco.sql
│   └── modelagem_der.sql
├── /src
│   ├── controller/
│   ├── model/
│   └── view/
└── README.md
