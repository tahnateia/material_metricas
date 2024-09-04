<h1 align="center">
<img src="https://img.shields.io/static/v1?label=AUC%20POR&message=TAH%20NA%20TEIA&color=7159c1&style=flat-square&logo=ghost"/>

<h3> <p align="center">AUC - Área Sob Curva </p> </h3>
<h3> <p align="center"> ================= </p> </h3>

>> <h3> Resumo </h3>

<p>
A Curva ROC (Receiver Operating Characteristic) é uma ferramenta essencial para avaliar a performance de um modelo de classificação, especialmente quando há desequilíbrio nas classes. A Curva ROC plota a Taxa de Verdadeiros Positivos (TPR) contra a Taxa de Falsos Positivos (FPR) em vários limiares de decisão.

- **Taxa de Verdadeiros Positivos (TPR)**, também conhecida como sensibilidade, é a proporção de positivos reais que foram corretamente identificados como positivos pelo modelo.
- **Taxa de Falsos Positivos (FPR)** é a proporção de negativos reais que foram incorretamente classificados como positivos.

Ao traçar essas taxas para diferentes limiares de decisão, a Curva ROC oferece uma visão detalhada de como o modelo se comporta em diferentes cenários. Uma Curva ROC mais alta indica um modelo que tem uma melhor capacidade de distinguir entre as classes.

A métrica <strong>AUC</strong> (Área Sob a Curva) quantifica a performance do modelo com base na Curva ROC. A AUC é o valor da área sob a Curva ROC e varia de 0 a 1:

- Um valor de AUC próximo de 1 indica um modelo excelente na separação das classes.
- Um valor de AUC próximo de 0.5 sugere que o modelo não é melhor que uma escolha aleatória.

A AUC é uma métrica valiosa, pois fornece uma medida agregada da performance do modelo ao considerar todos os limiares possíveis, oferecendo uma visão clara da sua capacidade geral de discriminação.
</p>


>> <h3> Sobre a aula </h3>

<p> Nesta aula você vai confrontar a métrica da CURVA ROC e da AUC em um problema simples de classificação de risco de colisão de asteroide. Usaremos um dataset tratado e obtido da NASA onde iremos testar se nossos dados estão balançeados ou não e iremos treinar um modelo de classificação, ao final, iremos testar a CURVA ROC dele. </p>
