# Projeto de Localizações com APIs

Este projeto utiliza a API do curso **Python for Everybody** (Dr. Chuck) para converter endereços em coordenadas geográficas (geocodificação) e armazená-los numa base de dados. No fim, gera um ficheiro `where.js` para visualização num mapa.

## 📂 Estrutura do projeto

- `Projeto_Localizacoes_com_APIs.ipynb` — Código principal em Python (Jupyter Notebook)
- `exemplo_where.data.txt.txt` — Lista de endereços (um por linha)
- `where.js` — Ficheiro gerado com coordenadas para uso em mapa

## ▶️ Como correr o projeto

1. Instale Python 3.x e o Jupyter Notebook (ou use Google Colab)
2. Coloque o ficheiro `exemplo_where.data.txt.txt` na mesma pasta
3. Corra o notebook
4. O script vai:
   - Aceder à API `https://py4e-data.dr-chuck.net/opengeo?`
   - Guardar os resultados em `opengeo.sqlite`
   - Gerar o ficheiro `where.js`

## 🔐 Nota sobre os dados

Este projeto foi feito com base no curso "Python for Everybody", que inclui uma API gratuita para fins educacionais.

> **Atenção:** Como o acesso aos dados originais do curso é restrito aos participantes, criei uma **base de dados de exemplo com moradas reais de locais conhecidos**, apenas para testes e demonstração.  
> Isto evita o uso indevido dos ficheiros originais protegidos por direitos de autor.

## ❗ Notas adicionais

- O ficheiro `opengeo.sqlite` **não está incluído** no repositório. Será criado automaticamente ao correr o notebook.
- O ficheiro `where.js` pode ser gerado ou consultado com dados de exemplo incluídos.
- Esta API tem limites — é apenas para testes educacionais.

## 📜 Licença

Este projeto segue o espírito educacional do curso [Python for Everybody](https://www.py4e.com/).
