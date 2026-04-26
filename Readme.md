# Nepali Date Picker Ecosystem 🇳🇵

Official repository for the **Nepali Date Picker** ecosystem, providing ready-to-use Bikram Sambat (BS) date picker components for modern web frameworks.

[![Support](https://img.shields.io/badge/Support-Bikram%20Sambat-red.svg?style=flat-square)](#)
[![Platforms](https://img.shields.io/badge/Platforms-Vue%203%20%7C%20Vue%202-blue.svg?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](./LICENSE)

---

## 🌐 Official Documentation

Full documentation, API references, and live examples are available at:
**[https://nepalidatepicker.sandip-ghimire.com.np/](https://nepalidatepicker.sandip-ghimire.com.np/)**

---

## 📦 Packages

This ecosystem includes specialized components for different frameworks:

### 💚 [Vue 3 Component](./Vue)
First-class Vue 3 component with full TypeScript support, v-model binding, and Composition API.
- **Package**: `nepali-datepicker-vue`
- **Docs**: [Vue 3 Reference](https://nepalidatepicker.sandip-ghimire.com.np/docs/Vue3/)

### 💚 [Vue 2 Component](./Vue2)
Fully compatible Vue 2 component with v-model binding and Options API support.
- **Package**: `nepali-datepicker-vue2`
- **Docs**: [Vue 2 Reference](https://nepalidatepicker.sandip-ghimire.com.np/docs/Vue2/)

### ⚛️ React Component
- **Status**: 🚧 Under Development (Coming Soon)

---

## ✨ Features

- **Accurate BS Dates**: Supports BS 1976 to 2100 with accurate month lengths.
- **Highly Customizable**: Control min/max dates, placeholders, disabled states, typing, and Saturday highlights.
- **Smart Positioning**: (Vue 3) Calendar auto-positions based on available viewport space.
- **TypeScript Support**: (Vue 3) Fully typed for a better developer experience.
- **Pure CSS**: Flexible styling with Vanilla CSS.

---

## 🚀 Quick Preview (Vue 3)

```vue
<script setup>
import { ref } from "vue";
import NepaliDatePicker from "nepali-datepicker-vue";
import "nepali-datepicker-vue/main.css";

const date = ref("");
</script>

<template>
  <NepaliDatePicker v-model="date" placeholder="YYYY-MM-DD" />
</template>
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue if you find a bug or have a feature request.

## 📄 License

This project is licensed under the **MIT License**.

Copyright © 2026-present **Sandip Ghimire**
