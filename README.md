# Pipeline de Integração de Dados para Fusão de Empresas

## 📌 Sobre o Projeto
Este projeto demonstra a criação de uma pipeline de dados para um cenário fictício de fusão entre duas empresas. O objetivo é coletar os dados das duas organizações, combiná-los e aplicar as transformações necessárias para unificação e análise.

## 🚀 Tecnologias Utilizadas
- **Python**: Para manipulação e transformação dos dados
- **Pandas**: Processamento e análise dos dados
- **SQL**: Armazenamento e consulta dos dados transformados

## 🔄 Fluxo da Pipeline
1. **Extração**: Os dados são coletados a partir de arquivos CSV representando as bases das empresas A e B.
2. **Transformação**:
   - Padronização de nomes e formatos
   - Remoção de duplicatas e dados inconsistentes
   - Unificação dos datasets com base em chaves comuns
3. **Carga**: Os dados consolidados são armazenados em um banco de dados SQL para análises futuras.

## 🛠 Como Executar o Projeto
### Pré-requisitos
Certifique-se de ter instalado:
- Python 3.x
- Pandas
- SQLite (ou outro banco de dados relacional de sua escolha)

### Passos
1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
    ```
2. Instale as dependências:

    ```python
    pip install -r requirements.txt
    ```
