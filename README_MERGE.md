# Projeto Unificado: Login + Geoportal

Este pacote combina o *telalogin* (tela de login e estrutura) com o *geoportal* como página Streamlit.

## Como usar

1. Crie/ajuste `auth_config.yaml` conforme seu projeto de login.
2. Instale dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Rode:
   ```bash
   streamlit run app.py
   ```
4. Após login, acesse a página **Geoportal** no menu lateral ou na barra de páginas.

## Estrutura
- `app.py` (do projeto telalogin)
- `pages/Geoportal.py` (conteúdo do geoportal integrado; removemos `st.set_page_config`)
- `images/`, `assets/` (se existirem no geoportal) copiados para a raiz
- `requirements.txt` unificado
