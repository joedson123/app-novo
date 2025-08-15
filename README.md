# Controle de Vendas — versão forçada para /mount/tmp no Streamlit Cloud
- No Cloud: o banco fica em `/mount/tmp/controle_vendas_app`.
- Localmente: para persistir, rode com `DB_DIR=./data`.

## Rodar
```bash
pip install -r requirements.txt
streamlit run app.py
# ou local com persistência:
DB_DIR=./data streamlit run app.py
```
