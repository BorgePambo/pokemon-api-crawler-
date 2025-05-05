 PokéAPI Data Extractor
 Este script Python realiza a extração de dados da PokéAPI, uma API pública que fornece informações sobre os Pokémon.
 O script percorre todas as páginas da API, coleta dados detalhados de cada Pokémon e os salva em dois formatos: .csv e .json.
 Funcionalidades

    Faz requisições à PokéAPI para obter a lista completa de Pokémon.
    Para cada Pokémon, coleta:
        id: Identificador único do Pokémon
        name: Nome do Pokémon
        is_default: Indica se é a forma padrão
        location_area: URL com as informações de localização do Pokémon
    Salva os dados em dois arquivos:
        pokemon.csv
        pokemon.json
🧰 Requisitos

    Python 3.6 ou superior
    Bibliotecas:
        requests
        os
        csv
        json

Você pode instalar as dependências com:

pip install requests

📂 Estrutura do Projeto

PokenAPI/
├── data/
│   ├── pokemon.csv       # Arquivo CSV gerado com os dados
│   └── pokemon.json      # Arquivo JSON gerado com os dados
├── app.py             # Seu script principal
└── README.md             # Este arquivo de documentação


Como Executar
    Clone o repositório ou baixe o script.
    Verifique se o caminho do diretório de saída (path) está correto para o seu sistema operacional.
    Execute o script:
    
