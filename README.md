# 🎨 Figma + 🧪 DevTools para QA
### Validação visual de interfaces na prática

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/0b286adb-2893-4d46-8140-926f7634d1ba" />

Este módulo complementa as metodologias ágeis trazendo um ponto essencial que muitos times ignoram:

👉 **Qualidade visual e fidelidade ao design**

---

## 🎯 Por que isso importa?

Em times ágeis, não basta funcionar.

👉 **Tem que funcionar certo e parecer certo.**

Erros visuais impactam diretamente:

- Experiência do usuário  
- Conversão (principalmente em e-commerce)  
- Credibilidade da marca  

---

## 🎨 Figma no QA

### 📌 O que é o Figma para o QA?

O Figma é a **fonte da verdade do layout**.

Tudo que está no produto deve seguir exatamente o que foi definido nele.

---

### 🚀 Importância do Figma na validação

Sem usar Figma, o QA:

- Valida “no olho”  
- Pode deixar passar erros visuais  
- Perde precisão  

Com Figma, o QA:

- Valida com exatidão  
- Identifica divergências claras  
- Garante **pixel perfect**  

---

### 🧠 O que validar no Figma

- Espaçamentos (margin / padding)  
- Tipografia (font-size, font-weight)  
- Cores (HEX)  
- Componentes (botões, inputs, cards)  
- Alinhamento  
- Responsividade  

---

### 💡 Dica prática

Use a tecla `ALT` para medir espaçamentos diretamente no Figma.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/fe638319-e603-4153-bb77-ef225cfcaae4" />

---

## 🧪 DevTools no QA

### 📌 O que é o DevTools?

O DevTools é a ferramenta que mostra o que realmente foi implementado no código.

---

### 🚀 Importância do DevTools

Sem DevTools:

👉 Você **acha** que está errado  

Com DevTools:

👉 Você **prova** que está errado  

---

### 🧠 O que validar no DevTools

- CSS aplicado  
- Margin / Padding (Box Model)  
- Fontes e cores reais  
- Dimensões (width / height)  
- Estados (`hover`, `active`, `focus`)  

---

### 📱 Validação Mobile

Com DevTools você pode:

- Simular dispositivos (iPhone, Android)  
- Testar responsividade  
- Identificar quebras de layout  
- Detectar scroll horizontal 🚨  

---

### ⚠️ Bugs comuns detectados

- Espaçamento diferente do Figma  
- Fonte incorreta  
- Elementos desalinhados  
- Layout quebrando no mobile  
- Botões com área clicável ruim  

---

## ⚔️ Figma vs DevTools

### 🎨 Figma = Design (Esperado)

- Define como deve ser  
- Guia visual  
- Fonte da verdade  

---

### 🧪 DevTools = Implementação (Real)

- Mostra o que foi feito  
- Código aplicado  
- Comportamento real  

---

### 🔥 Diferença prática

| Figma | DevTools |
|------|--------|
| Mostra o design ideal | Mostra o que está em produção |
| Define espaçamento de 24px | Pode mostrar 16px (bug) |
| Define cor #000 | Pode estar #111 (bug) |
| Define layout perfeito | Pode quebrar no mobile |

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/071b1571-56db-4ed8-9599-ad305781f238" />

---

## 🎯 Papel do QA

👉 Comparar os dois e encontrar divergências

---

## 🧪 Exemplo prático

**Cenário: Botão CTA**

- Figma: padding 24px  
- DevTools: padding 16px  

👉 **Resultado: BUG de layout**

---

## 🚀 Conclusão

Um QA de alto nível não valida só funcionalidade.

Ele valida:

- Experiência  
- Interface  
- Fidelidade ao design  

---

## 💣 Regra de ouro

👉 Figma mostra o que deveria ser  
👉 DevTools mostra o que realmente é  

👉 O QA garante que os dois sejam iguais  
