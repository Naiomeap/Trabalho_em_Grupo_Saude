# Trabalho_em_Grupo_Saude

### Descrição

#### Esse trabalho tem como intuito estudar a área da saúde, para identificar os municípios brasileiros mais adequados para a abertura de novos negócios nessa área.

Como existem muitos ***gaps*** na área da saúde, optamos por analisar os dados sobre a densidade de estabelecimentos da saúde, para identificar municípios que possui escassez de profissionais da saúde e/ou estabelecimentos da saúde. Nesses municípios, encontra-se oportunidades para abertura de clínicas multidisciplinares que ofereçam esse tipo de serviço, particulares ou em parceria com o governo.

#
**Estrutura do Repositório**

Este repo não tem divisões por pastas, contendo apenas os arquivos:

- [README.md](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/README.md): Este arquivo.
- [Trabalho_em_Grupo_Analise_Saude.ipynb](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/Entrega_Final_Trabalho_em_Grupo_Analise_Saude.ipynb): Notebook produzido em Google Colab com as análises.
- [Tabela_Compilada](https://github.com/Naiomeap/Trabalho_em_Grupo_Saude/blob/main/Tabela_Compilada.csv): Base de dados, contendo as variáveis demográficas a serem incluídas no modelo.

### Dicionário de Dados

O *dataset* final conta com os seguintes atributos:

- **CD_MUN** - Código do Município - tipo de dado (int64)
- **MUN** - Município - tipo de dado (object)
- **AR_TER_km2** - Área Territorial em Km² - tipo de dado (float64)
- **POP_EST** – Quantidade da população Estimada - tipo de dado (int64)
- **DENS_DEM** – Densidade Demográfica (número de habitantes por km²) - tipo de dado (float64)
- **ESC** - Escolaridade - tipo de dado (float64)
- **IDHM** - Índice de Desenvolvimento Humano (escala) - tipo de dado (float64)
- **MORT_INF** – Quantidade de mortalidade Infantil - tipo de dado (float64)
- **PIB_P_CAP** - Produto Interno Bruto Per Capta (valores nominais) - tipo de dado (float64)
- **MD_CIR_G** - Quantidade de Médico Cirurgião-Geral - tipo de dado (float64)
- **MD_CLIN** - Quantidade de Médico Clínico - tipo de dado (float64)
- **MD_GIN_OBS** - Quantidade de Médico Ginecologista-Obstetra - tipo de dado (float64)
- **MD_FAM** - Quantidade de Médico de Família e Comunidade - tipo de dado (float64)
- **MD_PED** - Quantidade de Médico Pediatra - tipo de dado (float64)
- **MD_GERI** - Quantidade de Médico Geriatra - tipo de dado (float64)
- **MD_URO** - Quantidade de Médico Urologista - tipo de dado (float64)
- **AS_SOC** - Quantidade de Assistente Social - tipo de dado (float64)
- **ENF** - Quantidade de Enfermeiro - tipo de dado (float64)
- **FISIO** - Quantidade de Fisioterapeuta - tipo de dado (float64)
- **FONO** - Quantidade de Fonoaudiólogo - tipo de dado (float64)
- **NUTRI** - Quantidade de Nutricionista - tipo de dado (float64)
- **ODONTO** - Quantidade de Odontologista - tipo de dado (float64)
- **PSICO** - Quantidade de Psicólogo - tipo de dado (float64)
- **PSIQ** - Quantidade de Psiquiatra - tipo de dado (float64)
- **POSTO** - Quantidade de Posto de Saúde - tipo de dado (float64)
- **CS_UBS** - Quantidade de Centro de Saúde / Unidade Básica de Saúde - tipo de dado (float64)
- **POLICL** - Quantidade de Policlínica - tipo de dado (float64)
- **HOSP_GER** - Quantidade de Hospital Geral - tipo de dado (float64)
- **HOSP_ESP** - Quantidade de Hospital Especializado - tipo de dado (float64)
- **PRT_SOC** - Quantidade de Pronto-Socorro Geral - tipo de dado (float64)
- **PRT_ESP** - Quantidade de Pronto-Socorro Especializado - tipo de dado (float64)
- **QTD_ESTAB** – Somatório da quantidade de estabelecimento (posto de Saúde, centro de saúde / unidade básica de saúde, policlínica, hospital geral, hospital especializado, pronto socorro geral e pronto socorro especializado) de saúde - tipo de dado (float64)
- **QTD_ESP** – Somatório da quantidade total de profissionais (psiquiatra, psicólogo, odontologista, nutricionista, fonoaudiólogo, enfermeiro, assistente social, médico urologista, médico geriatra, médico da família, médico pediatra, médico clínico, médico ginecologista-obstetra, médico cirurgião geral) da área da saúde - tipo de dado (float64)
- **TAXA_ESTAB** - Porcentagem da quantidade de estabelecimentos da saúde por quantidade de profissionais da saúde - tipo de dado (float64)

### Autora

- Naiome Alves Pereira

### Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE.md para mais detalhes.
