# FIAP - 1IADT - Grupo 28

Esta é a entrega da atividade da FASE 3 da POSTECH IA FOR DEVS (1IADT) da FIAP para

_**Grupo 28**_

## IMPORTANTE

Tivemos problemas durante a tentativa de fazer fine tuning com o modelo BERT do Google fazendo _Text Classification_. Deixamos detalhes no jupyter notebook _Fase3_TechChallenge.ipynb_.

Criamos um segundo jupyter notebook _(Fase3 - Tech Chalenge - Segunda Tentativa.ipynb)_ fazendo uma LoRA de um modelo _LLaMa_

Gostariamos que levassem em conta os 2 trabalhos, já que o primeiro consumiu mais de **60 horas de trabalho** em treinamento e testes.

## INTEGRANTES DO GRUPO 28

Guilherme Luiz Argentino Silva
guilherme.argentino@gmail.com

Gustavo Perri Galegale
gustavo.galegale@fiap.com.br

## INSTRUÇÕES (PRIMEIRA TENTATIVA)

1. Abra o Jupyter Notebook pelo botão dentro dele no colab ou faça o upload dele para o seu servidor
2. Caso use um servidor próprio: Altere a variável que contem a pasta de destino do checkpoint
3. Execute as instruções na ordem do arquivo
4. (Opcional) Altere outras variáveis para verificar diferenças de performance e precisão do resultado

## INSTRUÇÕES (SEGUNDA TENTATIVA)

1. Abra o Jupyter Notebook pelo botão dentro dele
2. Execute as instruções na ordem do arquivo
3. (Opcional) Para replicar os processos de Upload para o Hugging Face, é necessário um token. Veja mais em: https://huggingface.co/settings/tokens
 
## PUBLICAÇÕES

https://huggingface.co/rrantz/FIAP-1IADT-Grupo28
https://huggingface.co/datasets/rrantz/LF-Amazon-1.3M
https://huggingface.co/rrantz/FIAP-1IADT-Grupo28-lora-model

## REFERENCIAS

- https://pypi.org/project/gdown/
- https://huggingface.co/
- https://rocm.docs.amd.com/projects/HIP/en/docs-6.0.0/how_to_guides/install.html
- https://rocm.docs.amd.com/projects/radeon/en/latest/docs/install/native_linux/install-pytorch.html
- https://github.com/rstudio/reticulate/issues/1282
- https://stackoverflow.com/questions/72540359/glibcxx-3-4-30-not-found-for-librosa-in-conda-virtual-environment-after-tryin
- https://jupyter.org/install
- https://huggingface.co/docs/transformers/model_doc/bert
- https://www.debugpoint.com/linux-amdgpu-controller/
- https://github.com/ilya-zlobintsev/LACT/releases
- https://gitlab.com/corectrl/corectrl/
- https://community.amd.com/t5/pc-graphics/undervolting-a-6800xt-on-linux/td-p/524898
- https://unsloth.ai/
