# Configuração do ambiente de desenvolvimento para PICO Neo 3 Pro

Para instação dos softwares necessários seguir mesmos passos para instalação do android studio para o Quest 2.

### Requisitos

- Unreal Engine 4.27.2
- Android Studio
- PICO Neo 3 Pro (Versão PUI 4.8.17)

### Intruções

1. Criar novo projeto com as seguintes configurações:
- Blank
- C++ ou Blueprints
- Scalable 3D or 2D
- Mobile/Tablet
- No Starter Content
2. Baixar SDK do PICO no site do desenvolvedor (última versão se possível) e adicionar os plugins em uma pasta "Plugins" no root do projeto criado.
3. Basta iniciar o packaging direcionado a Android ASTC e utilizar o instalador gerado na pasta do cook.


### Ferramenta de preview
- Baixar preview do site do PICO
- Com o Neo 3 conectado ao computador utilize o comando no cmd: "adb install ..." e arraste o apk do preview para o cmd
- Instale o preview no windows e execute, ainda com o Neo 3 conectado ao óculos abra o aplicativo e reabra a Unreal