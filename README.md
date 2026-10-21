# Automação de emissão de notas fiscais no Oracle ERP R12

**Case de melhoria de processos, automação no-code e continuidade operacional com Dataload Classic**

Projeto aplicado a uma operação da indústria automobilística com produção **just-in-time**, envolvendo a emissão de notas fiscais de embalagem e a redução de atividades repetitivas no ERP Oracle R12.

> **Preservação do projeto:** os templates originais, as informações, os gráficos, os indicadores e a demonstração em vídeo foram mantidos. A descrição original, na íntegra e sem alteração de conteúdo, está arquivada em [DOCUMENTACAO_ORIGINAL.md](./DOCUMENTACAO_ORIGINAL.md).

## 1. Visão executiva

### Contexto e desafio de negócio

A emissão de notas fiscais de embalagem era realizada manualmente por diferentes colaboradores da equipe fiscal. A rotina envolvia trabalho repetitivo, consumia tempo da operação e exigia mecanismos de contingência para manter o atendimento em um ambiente produtivo just-in-time.

**Objetivo do projeto:** reduzir a execução manual dessa atividade por meio de automação com **Dataload Classic**, padronizando o carregamento das informações no Oracle ERP R12 e ampliando a capacidade de continuidade da operação.

### Solução adotada

- **Mapeamento funcional:** identificação e mapeamento dos campos do ERP utilizados na emissão.
- **Automação no-code:** criação de templates Dataload adequados aos diferentes tipos de nota fiscal.
- **Operação assistida:** preparação dos dados, parametrização dos comandos e execução em máquinas dedicadas.
- **Capacitação:** treinamento dos usuários para utilizar os templates e realizar as emissões.
- **Contingência:** elaboração de manuais e treinamento de profissionais de apoio (*backups*) para situações de indisponibilidade de pessoal.

Esses pontos resumem o trabalho já descrito no projeto original. **Não representam uma alteração dos fluxos ou dos scripts existentes.**

## 2. Minha atuação no projeto

O case evidencia competências relevantes para **Análise de Negócios, melhoria de processos e automação de rotinas empresariais**:

| Frente de atuação | Entrega documentada |
| --- | --- |
| Entendimento do processo | Análise da rotina fiscal e identificação das atividades repetitivas |
| Mapeamento funcional | Identificação dos campos e comandos necessários no Oracle ERP |
| Configuração da automação | Estruturação de templates com Dataload Classic para diferentes notas fiscais |
| Implantação operacional | Utilização de máquinas dedicadas à execução das atividades |
| Gestão do conhecimento | Treinamentos de usuários e orientação para equipes de apoio |
| Continuidade de negócio | Manuais e plano de contingência compatíveis com a operação just-in-time |

**Tecnologias e práticas presentes no case:** Oracle ERP R12 · Dataload Classic · Automação no-code · Mapeamento de processos · Padronização de rotinas · Treinamento de usuários · Continuidade operacional.

## 3. Artefatos originais — preservados

Os arquivos abaixo fazem parte do projeto e **não foram modificados**:

| Arquivo | Referência no repositório |
| --- | --- |
| DATALOAD AR BILLING.dld | [Abrir arquivo original](./DATALOAD%20AR%20BILLING.dld) |
| DATALOAD ORDER MANAGEMENT.dld | [Abrir arquivo original](./DATALOAD%20ORDER%20MANAGEMENT.dld) |
| Emissao_NF_Embalagem v1.dld | [Abrir arquivo original](./Emissao_NF_Embalagem%20v1.dld) |
| Templates_Contingencia-emissaodenota | [Abrir registro existente](./Templates_Contingencia-emissaodenota) |
| DOCUMENTACAO_ORIGINAL.md | [Ler o conteúdo anterior completo](./DOCUMENTACAO_ORIGINAL.md) |

A listagem preserva os **nomes e arquivos originais**; ela não redefine a responsabilidade técnica de cada template nem altera os comandos de automação.

## 4. Indicadores do projeto

Os dados a seguir reproduzem os resultados **já apresentados na documentação original**. A introdução da automação é situada **no final de maio**, e a descrição compara valores de janeiro e junho.

| Indicador | Janeiro | Junho |
| --- | ---: | ---: |
| Taxa de erros | **11%** | **6%** |
| Cumprimento de prazos | **35%** | **72%** |
| Satisfação do cliente | **51%** | **90%** |
| Rejeição de notas | **17%** | **3%** |
| Cancelamento de notas | **66%** | **18%** |

**Tempo de emissão — conforme o relato original:** aproximadamente **25 minutos em janeiro**, com referência à emissão de 10 notas, e **1 minuto por nota em junho**, considerando variações de acordo com a quantidade de itens. As unidades e condições desse indicador foram mantidas conforme a fonte, sem recalcular uma redução percentual.

### Gráficos e evidências publicados originalmente

![KPI original do projeto](https://github.com/BertaT2C/Projeto_Contingencia_Emissao_em_ERP/assets/99225701/8c73d12e-8b61-429f-b996-9f5bebc79149)

![Indicadores originais — gráfico 1](https://github.com/BertaT2C/Projeto_Contingencia_Emissao_em_ERP/assets/99225701/548194dc-e88b-493a-8fb6-88b4194b0685)

![Indicadores originais — gráfico 2](https://github.com/BertaT2C/Projeto_Contingencia_Emissao_em_ERP/assets/99225701/b0f811d2-a241-47ac-8c93-5f600346d8a3)

> **Importante:** as imagens, porcentagens e valores acima são os mesmos fornecidos no case. Nenhum novo KPI, ganho financeiro ou percentual foi criado nesta atualização.

## 5. Benefícios operacionais descritos

Os resultados apresentados indicam ganhos na eficiência da emissão, redução da necessidade de intervenção manual, melhoria da regularidade do processo e maior preparação das equipes para situações de contingência.

A combinação de **templates, capacitação e rotinas de backup** foi especialmente relevante em uma operação industrial que exige continuidade e agilidade.

![Animação original de apoio ao case](https://github.com/BertaT2C/Projeto_Automacao_EmissaodeNF_em_ERP/assets/99225701/46a0d1de-c551-4587-9ea4-3c0d3da7d908)

## 6. Demonstração do Dataload Classic

A demonstração já publicada no projeto foi preservada, incluindo sua sequência original de atividades:

1. **Configuração da ferramenta:** ajustar as configurações às necessidades específicas do processo.
2. **Inclusão dos comandos relacionados a cada campo:** definir instruções, formatos de entrada e validações.
3. **Alimentação dos dados a serem carregados:** preparar as informações em formulários ou planilhas específicas.
4. **Eliminação de pop-up:** lidar com alertas de confirmação ou mensagens de erro durante a execução.
5. **Execução do comando para alimentar um cadastro na web:** executar o preenchimento dos campos com os dados preparados.

Essa etapa corresponde à **demonstração da ferramenta** descrita no material original, sem substituir o projeto de emissão fiscal no Oracle ERP.

### ▶️ Vídeo original da demonstração

O endereço do vídeo foi mantido **exatamente como estava no README anterior**:

https://github.com/BertaT2C/Projeto_Contingencia_em_ERP/assets/99225701/980a4326-5316-4e1a-a383-c61110fe18b6

![Animação original de encerramento](https://github.com/BertaT2C/Projeto_Automacao_EmissaodeNF_em_ERP/assets/99225701/4e1cbda6-705e-442f-ac2b-7daf633e8894)

---

### Resumo para portfólio

**Projeto:** automação no-code de emissão de notas fiscais no Oracle ERP R12, com Dataload Classic.  
**Abordagem:** entendimento do processo, mapeamento de campos, configuração de templates, treinamento e contingência.  
**Contribuição:** simplificação de uma rotina fiscal repetitiva e apoio à continuidade operacional.  
**Evidências:** templates originais, gráficos de indicadores e vídeo demonstrativo preservados neste repositório.

*Documentação reorganizada para facilitar a compreensão do case; arquivos executáveis, fluxos e dados originais não foram alterados.*
