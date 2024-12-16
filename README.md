# NearBy

**NearBy** é um aplicativo mobile desenvolvido em React Native com Expo. Seu objetivo é oferecer cupons de desconto para usuários em estabelecimentos próximos. A aplicação utiliza diversas tecnologias e recursos modernos para entregar uma experiência dinâmica e funcional.

## Funcionalidades

- **Busca de estabelecimentos próximos** com base na localização.
- **Geração e leitura de QR Code**:
  - O estabelecimento gera um QR Code baseado no seu ID.
  - O usuário lê o QR Code para desbloquear o cupom de desconto.
- **Exibição de mapa** com a localização dos estabelecimentos.
- **Consumo de API** para obter dados de cupons e estabelecimentos.

## Tecnologias Utilizadas

### Frontend
- **React Native**: Desenvolvimento de interfaces mobile.
- **Expo Framework**: Simplificação do ambiente de desenvolvimento.
- **TypeScript**: Garantia de tipagem estática e maior segurança no código.
- **Expo Router**: Navegação baseada em arquivos.
- **StyleSheet**: Estilização de componentes.

### Backend
- **API Node.js**: Comunicação com o backend para obter informações sobre cupons e estabelecimentos.

## Conceitos Aplicados

- **Propriedades e Estados**: Gerenciamento dinâmico de dados dentro da aplicação.
- **Componentes Reutilizáveis**: Modularização para maior manutenção e organização do código.
- **Leitura de QR Code**: Uso da câmera para escanear e validar cupons.

## Como Executar o Projeto

1. Certifique-se de ter o **Node.js**, **npm** ou **yarn** e o **Expo CLI** instalados.

### Configurando o Frontend
2. Clone o repositório frontend:
   ```bash
   git clone https://github.com/gabrielabade/nearby.git
3. Instale as dependências:
   ```bash
   cd nearby
   npm install
4. Inicie o aplicativo frontend:
   ```bash
   npx expo start
5. Escaneie o QR Code gerado no terminal com o aplicativo Expo Go para rodar a aplicação no seu dispositivo físico ou utilize um emulador Android/iOS.

### Configurando o Backend
6. Clone o repositório backend:
   ```bash
   git clone https://github.com/gabrielabade/api-nearby.git
7. Instale as dependências:
   ```bash
   cd api-nearby
   npm install
8. Inicie o servidor backend:
   ```bash
   npm start
### Testando a Aplicação
9. Use o ID de um estabelecimento para gerar um QR Code.
10. Escaneie o QR Code com o aplicativo para desbloquear o cupom de desconto.