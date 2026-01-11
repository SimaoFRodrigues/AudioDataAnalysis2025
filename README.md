# Análise Musical de 2025

Este projeto consiste no desenvolvimento de um **dashboard interativo** para análise de características musicais (*audio features*) de músicas de 2025, utilizando **Quarto**, **Python**, **Observable JavaScript (OJS)** e **D3.js**.

O dashboard permite explorar métricas quantitativas relacionadas com ritmo, energia e emoção musical, bem como comparar resultados entre diferentes plataformas de streaming.

---

## Instruções de Execução

### Requisitos
- Quarto instalado
- Python 3.x
- Navegador web moderno (Chrome, Edge ou Firefox)

### Estrutura do Projeto
- `index.qmd` – ficheiro principal do dashboard
- `data/dataset_musicas2025.json` – dataset utilizado
- `assets/css/styles.css` – estilos personalizados
- `README.md` – documentação do projeto

### Execução
Abrir uma consola na pasta do projeto e executar:

```bash
quarto preview index.qmd
