# 🧠 Desafios de Processamento de Imagens com OpenCV

Este repositório reúne dois desafios desenvolvidos na disciplina **Processamento de Dados Bidimensionais**, utilizando **Python** e **OpenCV** no **Google Colab**.

O objetivo geral foi aplicar técnicas de **processamento digital de imagens** para identificar, contar e destacar objetos em imagens reais.

---

## 🧩 Desafio 1 — Colônias de Bactérias

**Objetivo:**  
Contar o número de colônias de bactérias em três imagens e representar cada colônia com uma cor diferente.

**Principais etapas:**
- Conversão para tons de cinza  
- Redução de ruído com filtro Gaussiano  
- Binarização adaptativa  
- Operações morfológicas para limpar ruídos  
- Contagem de componentes com `cv2.connectedComponents`  
- Colorização automática com tons HSV  

---

## 🔩 Desafio 2 — Parafusos

**Objetivo:**  
Contar o número de parafusos na imagem `Parafusos001`, destacando cada elemento com cores aleatórias.

**Principais etapas:**
- Conversão para tons de cinza e equalização de histograma  
- Binarização das imagens  
- Separação dos objetos 
- Colorização e contagem final dos elementos  

---

## 🧰 Ferramentas Utilizadas
- **Python 3.x**  
- **OpenCV**  
- **NumPy**  
- **Matplotlib**  
- **Google Colab**

---

## 🚀 Como Executar

1. Copie o código de cada desafio e cole em células separadas.  
2. Execute o código e envie as imagens quando solicitado.  
3. Veja o número total de objetos detectados e suas cores destacadas.

---

## 👨‍💻 Autor
**Jefferson Santos**  
Disciplina: *Processamento de Dados Bidimensionais*  

> 💡 Projeto desenvolvido para demonstrar o uso de técnicas de segmentação e contagem de objetos em imagens 2D.
