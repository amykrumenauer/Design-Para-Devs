# 🌈 Paleta de Cores com HSL (Arco-Íris) - Design Para Devs

Este projeto gera uma paleta de cores em formato de quadrados, utilizando o modelo de cores **HSL (Hue, Saturation, Lightness)** para criar um efeito de arco-íris.

## 🚀 Tecnologias Utilizadas

- React.js
- CSS Flexbox
- Modelo de cores HSL

## 🎨 Como Funciona?

Cada quadrado recebe uma cor baseada no **matiz (hue)** da escala HSL. A fórmula utilizada é:
backgroundColor: `hsl(${index * 12}deg 100% 50%)`
