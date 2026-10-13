# 🔎 Achados e Perdidos

Sistema proposto para organizar o registro, a consulta e a devolução de objetos encontrados em ambientes de grande circulação, com foco no contexto escolar.

## 📌 Sobre o projeto

O **Achados e Perdidos** é um projeto acadêmico de Tecnologia da Informação e Comunicação (PTIC), desenvolvido por estudantes do curso de Desenvolvimento de Sistemas da Etec Cidade Tiradentes.

A proposta é centralizar em uma plataforma digital o processo de recebimento, armazenamento, consulta e devolução de pertences perdidos, tornando o procedimento mais organizado, prático e seguro.

> **Status:** Projeto acadêmico de análise, documentação e prototipação. As funcionalidades descritas representam a proposta do sistema e não significam, necessariamente, que todas já estejam implementadas.

## 🎯 Objetivos

* Facilitar a localização de objetos perdidos.
* Organizar o cadastro e o armazenamento dos itens encontrados.
* Permitir a consulta de um catálogo digital.
* Controlar as solicitações e devoluções dos objetos.
* Aumentar a segurança por meio da validação presencial da propriedade.
* Facilitar o acompanhamento dos registros e a emissão de relatórios.

## ⚙️ Funcionalidades previstas

* **Catálogo público:** consulta dos objetos disponíveis, com pesquisa e filtros.
* **Cadastro de objetos:** registro das informações do item encontrado, incluindo características, foto e local de armazenamento.
* **Solicitação de retirada:** início do processo para reivindicar um objeto identificado no catálogo.
* **Registro de saída:** validação das informações do recebedor e registro formal da entrega.
* **Acesso de funcionários:** login para acessar as funções internas do sistema.
* **Cadastro de funcionários:** gerenciamento de contas realizado pelo gerente.
* **Relatórios:** consulta dos registros para acompanhamento da operação.
* **QR Code:** acesso facilitado ao catálogo digital.

## 👥 Perfis de usuário

| Perfil                      | Responsabilidades                                                              |
| --------------------------- | ------------------------------------------------------------------------------ |
| **Perdedor**                | Consultar o catálogo e solicitar a retirada de um possível pertence.           |
| **Achador**                 | Entregar um objeto encontrado e fornecer informações sobre ele.                |
| **Funcionário / Operador**  | Cadastrar e consultar objetos, verificar a propriedade e registrar devoluções. |
| **Gerente / Administrador** | Cadastrar funcionários e consultar relatórios gerenciais.                      |

## 🔄 Como funciona

1. Uma pessoa encontra um objeto e o entrega no ponto de atendimento.
2. O funcionário registra os dados do item e informa onde ele será armazenado.
3. O objeto fica disponível no catálogo público, conforme as regras previstas para consulta.
4. A pessoa que perdeu o pertence pesquisa no catálogo, que pode ser acessado por QR Code.
5. Ao identificar um possível objeto, ela solicita a retirada.
6. No balcão, o funcionário confere as informações para validar a propriedade.
7. Se a validação for aprovada, a entrega é registrada e o status do objeto passa para **Devolvido**. Caso contrário, a retirada é recusada.

## 🗂️ Organização dos arquivos

```text
prjAchados-e-Perdidos-main/
├── diagramas/
│   ├── diagrama1FuncGerente.png
│   └── diagrama2Perded.png
├── fluxogramas/
│   ├── fluxograma1Receber.png
│   └── fluxograma2Retirar.png
├── telas alta f/
│   └── Protótipos de alta fidelidade
├── telas baixa f/
│   └── Protótipos de baixa fidelidade
├── Achados e Perdidos.pdf
└── README.md
```

## 📐 Documentação do projeto

O material desenvolvido inclui:

* Documento principal do projeto;
* Fluxogramas dos processos de recebimento e retirada;
* Diagramas de casos de uso;
* Descritivos de casos de uso;
* Protótipos de baixa e alta fidelidade;
* Requisitos funcionais e não funcionais;
* Matriz de rastreabilidade.

O documento completo está disponível em [`Achados e Perdidos.pdf`](./Achados%20e%20Perdidos.pdf).

## 🖼️ Diagramas e fluxogramas

### Fluxogramas

**Recebimento de objeto**

![Fluxograma de recebimento](./fluxogramas/fluxograma1Receber.png)

**Retirada de objeto**

![Fluxograma de retirada](./fluxogramas/fluxograma2Retirar.png)

### Diagramas de casos de uso

**Funcionários e gerente**

![Diagrama de funcionários e gerente](./diagramas/diagrama1FuncGerente.png)

**Pessoa que perdeu o objeto**

![Diagrama do perdedor](./diagramas/diagrama2Perded.png)

## 🧰 Tecnologias e ferramentas

O repositório contém principalmente documentação, diagramas, fluxogramas e imagens dos protótipos. Como não foi definida uma stack definitiva de desenvolvimento no material analisado, as linguagens, os frameworks e o banco de dados não são apresentados como tecnologias já implementadas.

## 👨‍💻 Equipe

Projeto desenvolvido por estudantes da **Etec Cidade Tiradentes**, no curso de **Desenvolvimento de Sistemas**.

* Anderson Lima De Andrade
* Bleda Henrique da Hora Lopes
* Caio Henrique Moraes Ferreira
* Lucas Miguel Vitoria de Oliveira
* Melissa Barbosa Crepaldi
* Nicolas Anderson da Silva Santos
* Luan Evangelista de Souza Carvalho

**Professor orientador:** Prof. Everson
**Local:** São Paulo — SP
**Ano:** 2026

---

Este projeto foi desenvolvido com finalidade acadêmica, com o objetivo de planejar e documentar uma solução digital para organizar o processo de Achados e Perdidos.
