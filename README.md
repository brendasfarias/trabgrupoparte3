# trabgrupoparte3
# Trabalho-em-Grupo-Saude

### Descrição

#### Esse trabalho tem como intuito estudar a área da saúde, para identificar os municípios brasileiros mais adequados para a abertura de novos negócios nessa área.

Como existem muitos ***gaps*** na área da saúde, optamos por analisar os dados sobre crianças que nasceram com algum tipo de anomalia, para identificar municípios que não apresentam muitas clínicas que oferecem acompanhamento pré-natal para mulheres grávidas. Nesses municípios, pode-se encontrar oportunidades para abertura de clínicas que ofereçam esse tipo de serviço, particulares ou em parceria com o governo.

#
**Estrutura do Repositório**

Este repo não tem divisões por pastas, contendo apenas os arquivos:

- [README.md](https://github.com/Naiomeap/Trabalho-em-Grupo-Sa-de/README.md): Este arquivo.
- [Trabalho_em_Grupo_Analise_Saude.ipynb](https://github.com/Naiomeap/Trabalho-em-Grupo-Sa-de/blob/main/Trabalho_em_Grupo_Analise_Saude.ipynb): Notebook produzido em Google Colab com as análises.
- [Tabela_Compilada](https://github.com/Naiomeap/Trabalho-em-Grupo-Sa-de/blob/main/Tabela_Compilada.csv): Base de dados principal, contendo as variáveis demográficas a serem incluídas no modelo.
- [A011613189_28_143_208](https://github.com/Naiomeap/Trabalho-em-Grupo-Sa-de/blob/main/A011613189_28_143_208.csv): Arquivo auxiliar contendo os dados de nascimentos nos municípios.

### Dicionário de Dados

O *dataset* final conta com os seguintes atributos:


- **CD_MUN** - Código do Município
- **AR_TER_km2** - Área Territorial em Km²
- **POP_EST** – Quantidade da população Estimada
- **DENS_DEM** – Densidade Demográfica (número de habitantes por km²)
- **ESC** - Escolaridade
- **IDHM** - Índice de Desenvolvimento Humano (escala)
- **MORT_INF** – Quantidade de mortalidade Infantil
- **PIB_P_CAP** - Produto Interno Bruto Per Capta (valores nominais)
- **MD_CIR_G** - Quantidade de Médico Cirurgião-Geral
- **MD_CLIN** - Quantidade de Médico Clínico
- **MD_GIN_OBS** - Quantidade de Médico Ginecologista-Obstetra
- **MD_FAM** - Quantidade de Médico de Família e Comunidade
- **MD_PED** - Quantidade de Médico Pediatra
- **MD_GERI** - Quantidade de Médico Geriatra
- **MD_URO** - Quantidade de Médico Urologista
- **AS_SOC** - Quantidade de Assistente Social
- **ENF** - Quantidade de Enfermeiro
- **FISIO** - Quantidade de Fisioterapeuta
- **FONO** - Quantidade de Fonoaudiólogo
- **NUTRI** - Quantidade de Nutricionista
- **ODONTO** - Quantidade de Odontologista
- **PSICO** - Quantidade de Psicólogo
- **PSIQ** - Quantidade de Psiquiatra
- **POSTO** - Quantidade de Posto de Saúde
- **CS_UBS** - Quantidade de Centro de Saúde / Unidade Básica de Saúde
- **POLICL** - Quantidade de Policlínica
- **HOSP_GER** - Quantidade de Hospital Geral
- **HOSP_ESP** - Quantidade de Hospital Especializado
- **PRT_SOC** - Quantidade de Pronto-Socorro Geral
- **PRT_ESP** - Quantidade de Pronto-Socorro Especializado
- **SEM_ANOM** – Quantidade de crianças nascidas sem anomalia
- **NASC** – Número de Nascimento
- **ANOM** - Quantidade de crianças nascidas com alguma anomalia

### Autoras

- Brenda Farias

### Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE.md para mais detalhes.
