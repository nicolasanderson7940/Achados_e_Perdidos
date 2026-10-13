# Achados e Perdidos 🔎

## Sobre o projeto

O **Achados e Perdidos** é um projeto de sistema **web e mobile** voltado à gestão de objetos encontrados em ambientes de grande circulação, como escolas e outros espaços públicos.

Sua finalidade é **centralizar, organizar e rastrear o fluxo de pertences recolhidos**, substituindo controles manuais em planilhas e cadernos por uma plataforma digital mais prática e segura. A proposta busca facilitar a comunicação entre quem perdeu, quem encontrou e quem administra os objetos, além de tornar o processo de devolução mais organizado e confiável.

O sistema prevê a consulta a um catálogo digital por meio de **QR Code**, o registro de objetos encontrados, a solicitação de retirada e a validação presencial da devolução. Também contempla o controle de acessos, a gestão dos prazos e a emissão de relatórios operacionais.

> **Status:** projeto acadêmico documentado por meio de requisitos, diagramas, fluxogramas e protótipos. As funcionalidades descritas representam a solução planejada e não devem ser interpretadas como necessariamente implementadas.

## Finalidade

- Facilitar a localização e a recuperação de objetos perdidos.
- Centralizar as informações dos itens recolhidos e armazenados.
- Reduzir a burocracia e a dependência de registros manuais.
- Garantir maior controle sobre o armazenamento e a entrega presencial.
- Permitir o acompanhamento do status dos objetos e dos prazos de guarda.
- Melhorar a comunicação entre cidadãos e equipe responsável.

## Principais funcionalidades propostas ⚙️

### Catálogo digital e busca 🖥️

Acesso ao catálogo de objetos encontrados por meio de **QR Code** disponível presencialmente, com **barra de pesquisa** e **filtros** para ajudar a identificar pertences.

### Registro de objetos encontrados

Canal para que o **Achador** informe a entrega de um objeto e, conforme o fluxo previsto, registre seus dados e os dados do item encontrado.

### Solicitação de retirada 📤

O **Perdedor** poderá localizar um item no catálogo e iniciar uma solicitação de reivindicação para retirada presencial no balcão de atendimento.

### Triagem, guarda e devolução

O **Operador** realizará a triagem e o cadastro do objeto, registrará seu armazenamento, verificará as respostas às perguntas de validação e formalizará a entrega ao legítimo dono. Após a devolução, o status do item será atualizado para **“Devolvido”**.

### Administração e relatórios 📃

Uma interface administrativa permitirá gerenciar acessos e registros, acompanhar a operação e gerar **relatórios operacionais**.

### Controle de prazos

A solução prevê a automatização de prazos relacionados à guarda e à gestão dos objetos, conforme as regras definidas para o sistema.

## Perfis de usuários 💁

| Perfil | Responsabilidades |
| --- | --- |
| **Perdedor** (cidadão que perdeu um pertence) | Consultar o catálogo, pesquisar objetos e solicitar a retirada. |
| **Achador** (cidadão que encontrou um pertence) | Registrar a entrega e fornecer informações sobre o objeto encontrado. |
| **Operador** (funcionário de balcão) | Fazer triagem, cadastro, armazenamento, validação de propriedade e registro da devolução presencial. |
| **Administrador** | Gerenciar acessos e registros e consultar relatórios operacionais. |

## Fluxo de funcionamento proposto ↗️

1. Um objeto é encontrado e encaminhado ao ponto de atendimento.
2. O item é registrado, identificado e armazenado pela equipe responsável.
3. O catálogo digital disponibiliza as informações apropriadas para consulta.
4. A pessoa que perdeu o objeto acessa o catálogo via QR Code e utiliza busca ou filtros.
5. Ao identificar um possível pertence, inicia a solicitação de retirada.
6. No balcão, o operador verifica as informações e realiza as perguntas de validação.
7. Após a confirmação, o objeto é entregue presencialmente e seu status passa a **“Devolvido”**.

## Recursos e artefatos utilizados 🤳

A modelagem do sistema é apresentada por meio dos seguintes materiais:

- **Fluxograma:** representa as etapas e decisões do processo.
- **Diagrama de casos de uso:** identifica os atores e suas interações com o sistema.
- **Descritivo de casos de uso:** detalha o comportamento e as etapas das funcionalidades.
- **Protótipo de baixa fidelidade:** apresenta a organização inicial das telas e dos fluxos.
- **Protótipo de alta fidelidade:** demonstra a proposta visual das interfaces.
- **Lista de requisitos:** reúne necessidades e regras previstas para a solução.
- **Matriz de rastreabilidade:** relaciona requisitos aos elementos da documentação.

Esses recursos documentam o planejamento funcional e visual do projeto. **Não há indicação aqui de uma linguagem de programação, framework ou banco de dados específico**, pois essas tecnologias devem ser registradas apenas quando confirmadas.

## Benefícios esperados

Com a centralização das informações e a organização do atendimento, o projeto pretende reduzir perdas de registros, facilitar a localização dos pertences e tornar as devoluções mais transparentes. A consulta digital por QR Code aproxima o público do serviço, enquanto a conferência presencial preserva o controle da entrega.

## Contexto de desenvolvimento

Projeto acadêmico de análise, planejamento e prototipação de um sistema de **Achados e Perdidos** para uso em ambientes de circulação pública, com aplicação especialmente relevante no contexto escolar.

---

**Objetivo central:** conectar quem perdeu, quem encontrou e quem é responsável pela guarda dos objetos, promovendo uma devolução mais ágil, organizada e segura.
