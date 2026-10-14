# Mecânica e Relatividade (LEFA-MECREL) — 2026/2027

Repositório oficial dos cadernos computacionais interativos e recursos em Python para a unidade curricular de **Mecânica e Relatividade (LEFA-MECREL)** da **Licenciatura em Engenharia Física Aplicada (LEFA)** do **Instituto Superior de Engenharia do Porto (ISEP)**.

**Docente Responsável:** Cristóvão de Sousa Dias (`css@isep.ipp.pt`)  
**Departamento:** Departamento de Física (DFI) — ISEP / Politécnico do Porto

---

## 📚 Cadernos Computacionais (Google Colab)

Os cadernos laboratoriais foram desenvolvidos para apoiar as aulas teórico-práticas (TP), integrando computação simbólica (`SymPy`), computação numérica (`NumPy`, `SciPy`) e visualização interativa (`Matplotlib`, `ipywidgets`).

| Semana | Tema | Caderno Interativo | Descrição |
| :--- | :--- | :---: | :--- |
| **TP01** | Análise Dimensional, Ordens de Grandeza e Modelação Numérica | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristovaoDias/LEFA-MECREL/blob/main/Notebooks_Colab/TP01_Analise_Dimensional_e_Graficos.ipynb) | Verificação dimensional com SymPy, integração da velocidade de tsunamis $v = \sqrt{g h(x)}$, efeito de *shoaling* (Lei de Green) e regressão log-log da explosão Trinity (G.I. Taylor, 1945). |
| **TP02** | Simulação de Projéteis 2D e o Método de Euler | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristovaoDias/LEFA-MECREL/blob/main/Notebooks_Colab/TP02_Balistica_e_Metodo_Euler.ipynb) | Integração numérica pelo Método de Euler, quebra de simetria por arrasto aerodinâmico quadrático, ângulo ótimo de alcance real e análise de estabilidade com $\Delta t$. |
| **TP03** | Cinemática Curvilínea e Triedro de Frenet-Serret | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristovaoDias/LEFA-MECREL/blob/main/Notebooks_Colab/TP03_Cinematica_Curvilinea_e_Animacao.ipynb) | Triedro de Frenet $(\hat{u}_t, \hat{u}_n)$, decomposição da aceleração ($a_t$ e $a_n$), círculo de curvatura, raio local $\rho(t)$ e auditoria de código científico gerado por IA. |
| **TP04** | Dinâmica da Partícula I: Leis de Newton e Modelos de Atrito | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristovaoDias/LEFA-MECREL/blob/main/Notebooks_Colab/TP04_Dinamica_Atrito_Colab.ipynb) | Resposta dinâmica sob atrito de Coulomb (transição estático $\to$ cinético), escorregamento iminente e auditoria física de scripts gerados por LLMs. |
| **TP05** | Dinâmica da Partícula II: Máquinas de Atwood, Curvas Sobrelevadas e Arrasto | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CristovaoDias/LEFA-MECREL/blob/main/Notebooks_Colab/TP05_Sistemas_Acoplados_Curvas_Arrasto_Colab.ipynb) | Corpos acoplados com atrito, curvas sobrelevadas com margem $[v_{\min}, v_{\max}]$, velocidades terminais (Stokes vs quadrático), auditoria da *trajetória fantasma* em Zandvoort e engenharia de prompts. |


---

## 🚀 Como Utilizar

1. Clique no botão **"Open in Colab"** correspondente ao caderno da aula.
2. O Google Colab abrirá automaticamente uma cópia interativa na nuvem, sem necessidade de instalar software localmente.
3. Para guardar as suas alterações, selecione **Ficheiro > Guardar uma cópia no Drive** no menu do Colab.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.10+**
- **SymPy**: Álgebra computacional e análise dimensional.
- **NumPy & SciPy**: Cálculo matricial e integração numérica (`simpson`, `quad`).
- **Matplotlib**: Visualização gráfica e figuras para relatórios CDIO.
- **ipywidgets**: Sliders interativos para exploração paramétrica de modelos físicos.

---

*Departamento de Física (DFI) — Instituto Superior de Engenharia do Porto (ISEP)*
