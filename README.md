# 🍽️ MakroZone

[![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)](https://expo.dev)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

> Aplicativo mobile para controle de macros e alimentação diária

MakroZone é um aplicativo de rastreamento de macronutrientes que permite aos usuários registrar refeições e monitorar suas métricas diárias de nutrição (calorias, proteínas, carboidratos e gorduras).

---

## 📱 Funcionalidades

- **Dashboard Personalizado** - Visualize a data atual e resumo dos macros do dia
- **Cards de Macros** - Grid intuitivo mostrando totais de calorias, proteínas, carboidratos e gorduras
- **Registro de Refeições** - Adicione novas refeições com seus respectivos valores nutricionais
- **Histórico de Refeições** - Lista de refeições recentes e visão completa de todas as refeições

---

## 🛠️ Tecnologias

| Tecnologia | Descrição |
|------------|-----------|
| **Expo** | Framework e plataforma para desenvolvimento React Native universal |
| **React Native** | Framework para construção de aplicativos mobile nativos |
| **TypeScript** | Superset JavaScript com tipagem estática |
| **Expo Router** | Sistema de roteamento baseado em arquivos |

---

## 🚀 Começando

### Pré-requisitos

- Node.js (versão 18+)
- npm ou yarn
- Expo CLI

### Instalação

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/makrozone.git

# Entrar no diretório
cd makrozone

# Instalar dependências
npm install

# Iniciar o projeto
npx expo start
```

### Opções de Execução

Após iniciar o projeto, escolha uma opção:

- 📱 **Expo Go** - Sandbox limitado para testes rápidos
- 🤖 **Android Emulator** - Execute no Android Studio
- 🍎 **iOS Simulator** - Execute no Xcode (macOS)
- 🏗️ **Development Build** - Build de desenvolvimento completo

---

## 📁 Estrutura do Projeto

```
makrozone/
├── app/                    # Arquivos de rotas e telas (Expo Router)
│   ├── _layout.tsx         # Layout principal
│   ├── index.tsx           # Tela inicial (Dashboard)
│   ├── add-meal.tsx        # Tela de adicionar refeição
│   └── meals.tsx           # Tela de listar refeições
├── components/            # Componentes reutilizáveis
├── constants/             # Constantes e configurações
├── types/                 # Definições de tipos TypeScript
└── utils/                  # Funções utilitárias
```

---

## 🤝 Contribuição

Contribuições são bem-vindas! Siga os passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Add nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## 👤 Autor

**Marcio Nitao** - [GitHub](https://github.com/seu-usuario)

---

*Desenvolvido com ❤️ usando Expo e React Native*