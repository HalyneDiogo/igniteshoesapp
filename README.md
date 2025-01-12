# igniteshoesapp

## Projeto: Notificações Push com React Native e OneSignal

Este projeto tem como objetivo explorar a implementação de **Notificações Push** em aplicações mobile utilizando **React Native**, integrando o **Firebase Cloud Messaging (FCM)** e o **OneSignal**. O projeto cobre desde a configuração inicial de serviços de notificação para Android e iOS até a criação de filtros personalizados e tags para gerenciar e segmentar o envio de notificações.

---

## 🚀 Resumo do Projeto

Neste projeto, aprendi:
- Os **conceitos e aplicações das notificações push**, compreendendo quando e como utilizá-las de forma eficiente em aplicativos.
- A integração do **Firebase Cloud Messaging (FCM)** com o **OneSignal** para gerenciar o envio de notificações tanto para Android quanto para iOS.
- Configuração de notificações push no **Android** e **iOS**, incluindo ajustes necessários no **Xcode** e no painel de configurações do Firebase.
- O uso de **tags e segmentação** para personalizar o envio de notificações, tornando-as mais relevantes para os usuários.
- A implementação de **Deep Linking**, permitindo abrir partes específicas do aplicativo a partir de notificações.

---

## 🛠️ Ferramentas Utilizadas

### 1. Firebase Cloud Messaging (FCM)
- Configurado para gerenciar notificações push para dispositivos Android.
- Utilizado para gerar credenciais e conectar ao **OneSignal**.

### 2. OneSignal
- Plataforma para o gerenciamento centralizado do envio de notificações.
- Configuração de notificações push para Android e iOS.
- Implementação de **tags** para segmentação de usuários.
- Uso de **segmentation** e **audience filters** para notificações direcionadas.

### 3. Expo Dev Client
- Configurado para gerar builds nativas com o comando `expo prebuild`.
- Permite executar o aplicativo fora do **Expo Go** com suporte para bibliotecas nativas.

### 4. Xcode e APNS (Apple Push Notification Service)
- Configurado para habilitar notificações push em dispositivos iOS.
- Geração e importação de certificados de autorização para o envio de notificações.

### 5. React Native OneSignal
- Biblioteca utilizada para integrar a funcionalidade de notificações diretamente no código React Native.
- Configurada com o plugin **ExpoPlugin** para automatizar o processo de integração.

---

## 💡 Skills Desenvolvidos

### 1. Notificações Push
- Compreensão do ciclo de vida das notificações (em segundo plano, em primeiro plano e quando a aplicação está fechada).
- Habilidade de gerenciar notificações específicas para plataformas Android e iOS.

### 2. Segmentação de Usuários
- Uso de **tags** no OneSignal para identificar e classificar usuários.
- Personalização de notificações com filtros e segmentação por comportamento.

### 3. Integração Firebase + OneSignal
- Configuração de projetos no Firebase para integrar com o OneSignal.
- Geração de chaves e arquivos JSON necessários para a comunicação entre serviços.

### 4. Builds Nativas com Expo
- Utilização do comando `expo prebuild` para criar builds com suporte a bibliotecas nativas.
- Configuração avançada de arquivos como `app.json` para iOS e Android.

### 5. Desenvolvimento Mobile Multiplataforma
- Configuração e gerenciamento de fluxos de trabalho no React Native.
- Integração de funcionalidades específicas para Android e iOS (APNS e FCM).

### 6. Deep Linking
- Habilidade de criar links que direcionam os usuários para telas específicas do aplicativo a partir de notificações.

---


