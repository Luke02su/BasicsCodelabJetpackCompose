# 📱 Basics Codelab - Jetpack Compose

[![Kotlin](https://img.shields.io/badge/Linguagem-Kotlin-orange?logo=kotlin)](https://kotlinlang.org/)  
[![Android Studio](https://img.shields.io/badge/IDE-Android_Studio-brightgreen?logo=android-studio)](https://developer.android.com/studio)  
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)  

---

Um aplicativo Android desenvolvido em **Kotlin** utilizando o **Jetpack Compose**, baseado no codelab oficial do Google.  
O projeto demonstra os fundamentos da interface declarativa do Compose, incluindo **listas, animações, gerenciamento de estado e navegação simples**.

---

## 🚀 Funcionalidades

✅ Tela de **boas-vindas (Onboarding)** com botão de continuar  
✅ Exibição de uma **lista de cumprimentos** (“Hello, 0”, “Hello, 1”, etc.)  
✅ Cada item da lista possui uma **animação de expansão** suave ao clicar  
✅ Implementação de **estado lembrado e salvo** com `rememberSaveable`  
✅ Suporte a **modo claro e escuro (Dark Mode)**  
✅ Uso de **Material 3 (Material You)** com **Cards, Buttons e IconButtons**  
✅ Layouts responsivos com **LazyColumn**, `Row` e `Column`  

---

## 🎨 Demonstração Visual

📸 **Tela inicial (Onboarding)**  
Exibe uma mensagem de boas-vindas e um botão "Continue".

<p align="center">
   <img width="300" height="600" alt="Tela 1" src="https://github.com/user-attachments/assets/f26d3ab7-08ab-4fc2-88fb-e7cc1e1bc5d6" />
</p>

📜 **Lista de Cumprimentos (Greetings)**  
Mostra uma lista animada de cartões. Cada cartão pode ser expandido para revelar um texto adicional.

<p align="center">
   <img width="300" height="600" alt="Tela 1" src="https://github.com/user-attachments/assets/63b8c61b-146e-4f48-a65a-99a154d2ee37" />
</p>

---

## ⚙️ Tecnologias Utilizadas

- 🧠 **Kotlin**
- 🧱 **Jetpack Compose**
- 🎨 **Material Design 3**
- 🌀 **Animações com `animateContentSize()`**
- 💾 **Gerenciamento de estado com `rememberSaveable`**
- 🌙 **Suporte a Dark Theme**
- 🧰 **Android Studio Koala | Compose Preview**

---

## Autor do código 💻👨‍💻
```kotlin
fun main() {
    println("Code by Lucas Samuel Dias!")
    println("Welcome to the Basics Codelab using Jetpack Compose!")
}

