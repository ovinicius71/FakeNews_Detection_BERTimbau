# T2 — Detecção de Fake News (Resumo Rápido)

Projeto simples para comparar dois classificadores baseados em **BERTimbau** para detecção de fake news em português.

## O que tem aqui

* Notebook principal: `/mnt/data/FakeNews_Detection_BERTimbau.ipynb`

## Como rodar (rápido)

1. Abra o notebook: `jupyter lab /mnt/data/T2_FakeNews_Detection_BERTimbau_V3 (1).ipynb`
2. Execute as células na ordem. O notebook já contém as seções de:

   * carregamento e tokenização dos dados
   * definição dos modelos (baseline e variante)
   * treino, avaliação e geração de figuras

## Dependências principais

* Python 3.8+
* `torch`, `transformers`, `pandas`, `scikit-learn`, `matplotlib`, `umap-learn`

## Observações

* Recomendo usar GPU para treinar (fine-tuning do BERT).
* Há um snippet pronto para **early stopping** e para testar várias épocas/seeds.

---