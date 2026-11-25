# venv-e-pip-install

Carrossel de 7 slides (JPG). Versão TOFU. Texto usado na publicação pelo Buffer (Instagram, Facebook e TikTok).

## Legenda do Instagram e do Facebook

```
venv e pip install: passou na sua máquina. E na do time?

O venv é uma pasta com as bibliotecas só daquele projeto.
O pip install traz a biblioteca, e o pip freeze anota as versões no requirements.txt.
Com esse arquivo no repositório, o time instala igual com pip install -r requirements.txt.

Salve este post para revisar depois.

#testedesoftware #python #pytest #automacaodetestes
```

## Primeiro comentário (Instagram e Facebook, só no plano pago do Buffer)

```
Desafio: qual comando gera o requirements.txt? Responde só o comando.
```

## TikTok

Título:

```
venv e pip install: passou na sua máquina. E na do time?
```

Legenda:

```
O venv é uma pasta com as bibliotecas só daquele projeto.
O pip install traz a biblioteca, e o pip freeze anota as versões no requirements.txt.
Com esse arquivo no repositório, o time instala igual com pip install -r requirements.txt.

Salve este post para revisar depois.

#testedesoftware #python #pytest #automacaodetestes
```

## Texto alternativo

| Slide | Arquivo | Texto alternativo |
| --- | --- | --- |
| 1 | `01.jpg` | Passou na sua máquina. E na do time? |
| 2 | `02.jpg` | venv: uma caixa de bibliotecas por projeto. O que você instala no venv fica só naquele projeto. O Python da máquina continua limpo. Gráfico: O Python da máquina no alto. Embaixo, dois projetos, cada um com a sua pasta .venv e as suas bibliotecas: pytest na loja, Robot Framework no app. |
| 3 | `03.jpg` | 4 comandos para preparar o projeto. Código PowerShell, na pasta do projeto: python -m venv .venv / .\.venv\Scripts\Activate.ps1 / pip install pytest / pip freeze > requirements.txt. Cria a caixa, a pasta .venv. Entra nela, no Mac e no Linux: source .venv/bin/activate. Instala, o pytest entra só neste projeto. Anota, as versões vão para o requirements.txt. |
| 4 | `04.jpg` | Venv novo vem vazio. saída real · Python 3.11 · 25/11/2026. Saída do terminal: > python -c "import pytest" / Traceback (most recent call last): / File "<string>", line 1, in <module> / ModuleNotFoundError: No module named 'pytest' / > pip install pytest / Installing collected packages: pygments, pluggy, packaging, iniconfig, colorama, pytest / Successfully installed colorama-0.4.6 iniconfig-2.3.1 packaging-26.4 pluggy-1.7.0 pygments-2.21.0 pytest-9.2.0 / > pytest -q / 1 passed in 0.02s. |
| 5 | `05.jpg` | O requirements.txt vai junto com o teste. Código requirements.txt: colorama==0.4.6 / iniconfig==2.3.1 / packaging==26.4 / pluggy==1.7.0 / Pygments==2.21.0 / pytest==9.2.0. outro venv, como na máquina do colega. Saída do terminal: > pip install -r requirements.txt / Successfully installed Pygments-2.21.0 colorama-0.4.6 iniconfig-2.3.1 packaging-26.4 pluggy-1.7.0 pytest-9.2.0 / > pytest -q / 1 passed in 0.00s. |
| 6 | `06.jpg` | Projeto pronto para o time. Um venv por projeto. Ative antes de instalar. pip install traz a biblioteca. pip freeze anota as versões. O time instala igual com -r. |
| 7 | `07.jpg` | Próximo post: “10” não é 10. Salve este post para revisar depois. |
