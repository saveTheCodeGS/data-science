# 🔥 Análise de Incêndios Florestais nos Estados Unidos

## 🌎 Descrição do Projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados sobre **incêndios florestais nos Estados Unidos**, identificando padrões sazonais, causas predominantes e os estados mais afetados. A partir dessa análise, são propostas recomendações que podem auxiliar na prevenção e combate a incêndios, especialmente utilizando tecnologias como **drones, sensores remotos e inteligência artificial**.

---

## 🎯 Objetivos

- 🔥 Analisar as principais **causas** dos incêndios.
- 📅 Verificar se há **sazonalidade** nos eventos.
- 📍 Identificar os **estados mais afetados**.
- 🚁 Propor soluções baseadas em **tecnologia e análise de dados** para prevenção e mitigação.

---

## 🧠 Variáveis do Dataset

- `STATE` — Estado onde ocorreu o incêndio
- `FIRE_YEAR` — Ano da ocorrência
- `FIRE_MONTH` — Mês da ocorrência
- `FIRE_CAUSE` — Causa do incêndio (Humana, Natural, Desconhecida)
- `FIRE_SIZE` — Tamanho do incêndio (acres)
- `DISCOVERY_DATE` — Data de início
- Outras variáveis auxiliares: latitude, longitude, código do incidente, etc.

---

## 📊 Principais Visualizações e Insights

### 🗓️ Sazonalidade  
- 🔥 Picos claros nos meses de **junho, julho, agosto e setembro**.

### 🔥 Causas  
- ✅ **Causas humanas predominam**, com atividades como queima de resíduos, incêndios criminosos e negligência.

### 📍 Estados mais afetados  
1. **California**  
2. **Texas**  
3. **Georgia**  

### 🚩 Outliers e Tamanho dos Incêndios  
- Grande quantidade de incêndios pequenos, mas alguns eventos ultrapassam **600.000 acres**, causando enorme impacto ambiental.

---

## 🚀 Tecnologias Utilizadas

- **Python 3.10**
- **Pandas** — Manipulação de dados
- **Matplotlib** e **Seaborn** — Visualização de dados
- **Plotly** — Gráficos interativos
- **Jupyter Notebook** — Ambiente de desenvolvimento
- **Google Colab** — Execução em nuvem (opcional)

---

## 🛠️ Instalação e Execução

### 1️⃣ Clone o repositório:

```bash
git clone https://github.com/seu-usuario/incendios-florestais.git
```

### 2️⃣ Crie um ambiente virtual (opcional, mas recomendado):

```bash
  python -m venv venv
  source venv/bin/activate  # Linux/macOS
  venv\Scripts\activate     # Windows
```

### 3️⃣ Instale as dependências:

```bash
pip install -r requirements.txt
```

### 4️⃣ Execute os notebooks ou scripts Python na pasta /scripts ou via Jupyter/Colab.

## 💡 Recomendações Finais

- 🚁 Drones e sensores térmicos podem ser usados para monitoramento em tempo real.
- ⚠️ Focar em fiscalização e campanhas educativas nos meses de maior risco (junho a setembro).
- 🗺️ Criar mapas de risco dinâmicos, atualizados com dados climáticos e históricos.
- 🔥 Monitorar especialmente os estados da California, Texas e Georgia, que concentram o maior número de ocorrências.

## 📜 Licença

Este projeto está sob licença MIT — veja o arquivo LICENSE para mais detalhes.

## 🤝 Colaboradores

👤 João Victor Soave — Data Analyst e Desenvolvedor do Projeto
👨‍🏫 Professor — Fernando Nemec
