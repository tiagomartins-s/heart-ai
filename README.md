# HeartAI – Fase 1: Batimentos de Dados  

Este repositório faz parte do projeto **HeartAI**, desenvolvido no curso de Inteligência Artificial da FIAP, dentro da metodologia **PBL (Project Based Learning)**.  
Na **Fase 1 – Batimentos de Dados**, o objetivo é reunir, organizar e compreender dados cardiológicos que futuramente alimentarão os módulos inteligentes do HearAI, servindo de base para análises com **Machine Learning, NLP e Visão Computacional**.  

📂 **Link para os dados completos (Google Drive):**  
[CardioIA – Base de Dados](https://drive.google.com/drive/folders/1T1V9iRK1SZ568vIerU06xr6OJzmx8nbz?usp=drive_link)  

---

## 📊 Parte 1 – Dados Numéricos (IoT)  

No arquivo [`dados_cardiacos_simulados.csv`](https://drive.google.com/drive/folders/1T1V9iRK1SZ568vIerU06xr6OJzmx8nbz?usp=drive_link) há um dataset **simulado** contendo informações de pacientes cardíacos, com mais de 100 linhas e variáveis como:  

- **Idade**  
- **Sexo**  
- **Pressão arterial**  
- **Colesterol**  
- **Histórico de doenças cardíacas**  
- **Sintomas relatados**  
- **Frequência cardíaca**  

### 🔎 Relevância Clínica  
Essas variáveis são fundamentais para a triagem de pacientes e para o treinamento de modelos preditivos em saúde:  

- **Idade e sexo:** fatores de risco importantes em doenças cardiovasculares.  
- **Pressão arterial e colesterol:** métricas diretas de risco de hipertensão e aterosclerose.  
- **Histórico e sintomas:** fornecem contexto clínico para modelos preditivos.  
- **Frequência cardíaca:** indicador direto da função cardíaca em tempo real.  

O dataset pode ser explorado em modelos de **classificação de risco cardíaco**, **análise de padrões de sintomas** e **previsão de eventos cardíacos**.  

---

## 📑 Parte 2 – Dados Textuais (NLP)  

Na pasta [`docs`](./docs) foram adicionados dois textos:  

1. **Texto Técnico – Prevenção e Diagnóstico de Doenças Cardíacas**
   - Aborda a importância da **prevenção com hábitos saudáveis**, diagnóstico precoce e exames como ECG, ecocardiograma e teste ergométrico.  
   - Pode ser usado para **extração de sintomas**, **identificação de exames relevantes** e **classificação de recomendações médicas**.  

2. **Texto Literário – O Coração e o Tempo**
   - Um olhar poético sobre o coração, relacionando-o com o tempo, emoções e escolhas.  
   - Pode ser utilizado para **análise de sentimentos**, **identificação de metáforas** e **exploração de narrativas relacionadas à saúde**.  

### 🔎 Relevância Clínica e Tecnológica  
Esses textos podem ser explorados por algoritmos de **Processamento de Linguagem Natural (NLP)** para:  

- **Extração automática de sintomas** relatados em textos médicos.  
- **Análise de sentimentos** em narrativas literárias sobre saúde.  
- **Classificação de tópicos** para organizar grandes bases de artigos em saúde.  

Essas análises ajudam a **conectar dados clínicos objetivos com percepções subjetivas de pacientes** e literatura em saúde.  

---

## 🖼️ Parte 3 – Dados Visuais (Visão Computacional)  

Na pasta [`IMAGENS`](https://drive.google.com/drive/folders/1T1V9iRK1SZ568vIerU06xr6OJzmx8nbz?usp=drive_link) estão disponíveis mais de 100 imagens médicas, representando **exames de ECG**.  


### 🔎 Relevância Clínica e Tecnológica  
As imagens serão utilizadas em algoritmos de **Visão Computacional (VC)** para:  

- **Detecção de padrões** em traçados de ECG.  
- **Identificação de bordas e ondas P, QRS e T**.  
- **Reconhecimento de anomalias** como arritmias, bloqueios ou sinais de infarto.  

Esse tipo de análise permite a criação de sistemas de **triagem automática**, **assistência remota** e **monitoramento em tempo real** de pacientes.  

---

## 🚀 Conclusão  

Com a integração desses três tipos de dados — **numéricos, textuais e visuais** — o projeto HeartAI dá os primeiros passos para a construção de uma base sólida que permitirá desenvolver modelos inteligentes de apoio à saúde cardiovascular.  

A governança dos dados e a preocupação com vieses são pontos centrais neste processo, garantindo que as soluções futuras sejam **éticas, confiáveis e úteis para médicos e pacientes**.  

---

### 📂 Estrutura do Repositório  
```
CardioIA/
│── README.md
│── docs/
│ ├── texto_tecnico_cardiologia.txt
│ ├── texto_literario_cardiologia.txt
```


