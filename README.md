# 💧 Sistema de Classificação do Consumo de Água

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Interface-Tkinter-2C5E1A?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?style=for-the-badge&logo=github&logoColor=white)
![Sustentabilidade](https://img.shields.io/badge/Energia-Sustentável-00A86B?style=for-the-badge&logo=leaflet&logoColor=white)

## 🎯 Objetivo do sistema

O **Sistema de Classificação do Consumo de Água** analisa o consumo mensal de um imóvel e apresenta uma orientação de acordo com o tipo selecionado e a quantidade de água consumida.

O usuário pode selecionar um dos seguintes tipos de imóvel:

- Comercial
- Casa
- Apartamento

Depois, o sistema classifica o consumo como econômico, moderado ou excessivo. Para imóveis comerciais, informa que deve ser consultado o plano corporativo.

## 🛠️ Tecnologias utilizadas

- **Python 3**: linguagem utilizada para desenvolver o programa.
- **Tkinter**: biblioteca usada para criar a interface gráfica.
- **Git e GitHub**: ferramentas para versionamento e armazenamento do projeto.

## ▶️ Como executar

### 1. Verifique se o Python está instalado

No terminal, execute:

```bash
python3 --version
```

### 2. Execute o programa

Abra o terminal na pasta em que o arquivo do programa está salvo e execute:

```bash
python3 consumo-agua.py
```

## 📋 Regras de classificação

| Tipo de imóvel | Consumo | Resultado |
|---|---:|---|
| Comercial | Qualquer valor | Tarifa comercial |
| Apartamento | Menor que 10 m³ | Consumo econômico |
| Apartamento | A partir de 10 m³ | Consumo moderado |
| Casa | Até 25 m³ | Consumo moderado |
| Casa | Acima de 25 m³ | Consumo excessivo |

## 🌱 Sustentabilidade

O projeto incentiva o uso consciente da água e ajuda a identificar consumos elevados que podem indicar desperdício ou vazamentos.

## 👤 Autor

Desenvolvido por **Derick Prado**.
