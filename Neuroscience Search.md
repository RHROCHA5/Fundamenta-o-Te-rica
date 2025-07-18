# Teoria Fundamental: O Impacto Eletromagnético na Dinâmica Neural e na Patogênese da Esclerose Múltipla

## 🎯 Visão Geral do Projeto

Este repositório abriga a fundamentação teórica de uma pesquisa inovadora focada na **interação de campos eletromagnéticos (CEMs) com sistemas neurais**, 
com o objetivo principal de **elucidar seu papel como um fator causal ou contribuinte na patogênese da Esclerose Múltipla (EM)**. 
Utilizando modelagem computacional, este trabalho busca explorar mecanismos pelos quais os CEMs podem influenciar a dinâmica eletrofisiológica neuronal e, consequentemente, a integridade da mielina.

## 💡 Hipótese Central

A Esclerose Múltipla (EM) é uma doença neurodegenerativa complexa do Sistema Nervoso Central (SNC), caracterizada pela desmielinização e um processo autoimune que danifica a bainha de mielina. Embora sua etiologia seja multifatorial, a busca por fatores ambientais permanece crítica.

Nossa hipótese central propõe que **campos eletromagnéticos (CEMs) variáveis no tempo podem atuar como um fator causal ou contribuinte na patogênese da Esclerose Múltipla, 
elucidando seu impacto direto na dinâmica neural**. Argumenta-se que a interação desses CEMs com o tecido neural pode induzir um "estresse neural" que, 
a longo prazo, **compromete a integridade estrutural e a composição lipídica essencial da bainha de mielina**. A degradação resultante da mielina pode levar à sua **disfuncionalidade ou exposição de neoantígenos**,
tornando-a um alvo para o reconhecimento e subsequente ataque pelo sistema imune, desencadeando ou exacerbando o processo autoimune característico da EM. 
Tal processo modularia diretamente a dinâmica eletrofisiológica neuronal, mimetizando e/ou agravando a disfunção observada na EM.

## 📚 Fundamentação Teórica

Nossa teoria fundamenta-se na seguinte formulação matemática:

### 1. Modulação da Ativação Neuronal por CEMs Variáveis:

A interação primária é modelada pela variação temporal do campo magnético ((-∂B/∂t)), um componente do CEM que, por indução eletromagnética (Lei de Faraday), 
gera um campo elétrico no tecido neural. Este campo elétrico induzido é postulado como modulador direto da **função de ativação do neurônio Δσ)**.
Consequentemente, a taxa de variação do estado do neurônio (Z') é alterada em função de seu estado basal (Z) e da influência do CEM.

A equação que descreve essa interação é:

**Equação Z linha:** (Z'= Z + Δσ * (-∂B/∂t))

Onde:

* **Z'**: Representa a taxa de variação do estado do neurônio (neurônio "estressado" ou com função alterada).

* **Z**: Corresponde ao estado basal do neurônio (em ausência de perturbações significativas do CEM).

* **Δσ**: É a variação da função de ativação do neurônio, diretamente influenciada pela presença do CEM variável.

* **(-∂B/∂t)**: Denota a taxa de variação do campo magnético em relação ao tempo, servindo como o estímulo eletromagnético indutor primário.

### 2. Quantificação da Disfunção e Dissipação de Correntes Iônicas:


A disfunção resultante do "estresse neural" ou da desmielinização é quantificada através da análise do movimento e da dissipação das correntes iônicas (C.I.), essenciais para a propagação do impulso.

A velocidade de propagação ou a dissipação das C.I. pode ser expressa por:

**Equação de Velocidade** (V = λ/t)

Onde:

* **V**: Representa a velocidade das correntes iônicas ou uma taxa de dissipação (e.g., [comprimento]/[tempo] ou [taxa de fluxo de corrente]).

* **λ**: É o comprimento percorrido pelo impulso ou a dimensão espacial em análise.

* **t**: Corresponde ao tempo de propagação ou período de observação.

Adicionalmente, propõe-se que a taxa de estresse do neurônio ($Z'$) pode ser diretamente correlacionada à circulação da velocidade das correntes iônicas ao longo de um caminho fechado (∮V.dl). 

Esta formulação permite a avaliação quantitativa do impacto do CEM e da disfunção neuronal em diferentes regiões afetadas pela desmielinização da EM:

**Equação da Integral** (∮V.dl = Z')

Esta integral de linha (ou de superfície, dependendo da modelagem espacial) é utilizada para quantificar o movimento das correntes iônicas induzidas, 
fornecendo uma métrica para o "estresse" ou a "perda funcional" que se manifesta na desmielinização.

Acreditamos que, ao explorar computacionalmente esses mecanismos, podemos **elucidar o papel dos CEMs como um fator etiológico ou exacerbador na Esclerose Múltipla**, 
contribuindo para uma compreensão mais profunda dessa complexa patologia e, em última instância, **buscando a causa** dessa doença neurodegenerativa.

## 💻 Ferramentas e Tecnologias

Embora este repositório atualmente contenha a fundamentação teórica, a parte computacional do projeto será desenvolvida utilizando as seguintes bibliotecas e ferramentas:

* **NumPy:** Para operações numéricas e manipulação de arrays.
* **Brian2:** Para simulações de redes neurais e modelagem de neurônios biofisicamente detalhados.

## 🚀 Próximos Passos

O próximo estágio deste projeto envolve a implementação computacional dos modelos propostos, a realização de simulações e a análise dos resultados para validar e aprofundar nossa hipótese.

## 🤝 Contribuições

Este projeto está em fase inicial, focado na fundamentação teórica. Contribuições futuras para o código e expansões da teoria serão bem-vindas. Por favor, leia a seção de Licenciamento antes de contribuir.

## 📄 Licenciamento

Este projeto adota um regime de licenciamento duplo para garantir a clareza e a conformidade legal para diferentes tipos de conteúdo:

* **Código-fonte:** (arquivos `.py`, scripts, etc.)
    * Licenciado sob a **[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)**.
    * Encontre os termos completos da licença no arquivo **[LICENSE](LICENSE)** deste repositório.

* **Conteúdo Criativo e Documentação:** (textos, figuras, arquivos Jupyter Notebook - `.ipynb`, etc.)
    * Licenciado sob a **[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)**.
    * Encontre os termos completos da licença no arquivo **[LICENSE-CC.md](LICENSE-CC.md)** deste repositório.

**Você é livre para:**
* **Compartilhar** — copiar e redistribuir o material em qualquer suporte ou formato, *exceto para fins comerciais*.
* **Adaptar** — remixar, transformar, e criar a partir do material para qualquer fim, *exceto para fins comerciais*.

**Desde que você siga os termos da licença, que incluem:**
* **Atribuição** — Você deve dar o crédito apropriado, prover um link para a licença, e indicar se mudanças foram feitas. Você pode fazê-lo de qualquer forma razoável, mas não de maneira que sugira que o licenciador o endossa ou o seu uso.
* **Não Comercial** — Você não pode usar o material para fins comerciais.
* **CompartilhaIgual** — Se você remixar, transformar, ou criar a partir do material, tem de distribuir as suas contribuições sob a mesma licença que o original.

---

**Autor:** [Rhuan Pablo de Paula Rocha/RHROCHA5]

**Contato:** [LinkedIn](https://www.linkedin.com/in/rhuan-rocha-a24573223/)
