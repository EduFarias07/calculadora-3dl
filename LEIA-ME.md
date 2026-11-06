# Calculadora 3DL — projeto Android

Este projeto empacota a versão web atual da Calculadora 3DL em um aplicativo Android offline, usando Capacitor.

## Gerar o APK usando somente o celular

1. Extraia este ZIP no celular.
2. Entre em https://github.com e crie um repositório novo, por exemplo `calculadora-3dl`.
3. Envie **todos os arquivos e pastas** deste projeto para a raiz do repositório. É importante incluir a pasta oculta `.github/workflows`.
4. No GitHub, abra a aba **Actions** e selecione **Compilar APK - Calculadora 3DL**.
5. Toque em **Run workflow** e confirme.
6. Aguarde a execução terminar com status verde.
7. Abra a execução concluída e, em **Artifacts**, baixe `Calculadora-3DL-APK`.
8. Extraia o ZIP baixado e instale `app-debug.apk`. Talvez seja necessário permitir a instalação de apps desta fonte nas configurações do Android.

## Observações

- O APK gerado é de **depuração (debug)**, adequado para instalar e testar no seu próprio aparelho.
- Não é um APK assinado para publicação na Play Store.
- O aplicativo inclui a página atual em `www/index.html`; para atualizar a calculadora, substitua esse arquivo e execute novamente o workflow.
- Os dados salvos no armazenamento local do aplicativo ficam no próprio aparelho. Desinstalar o aplicativo pode apagar esses dados; faça backup antes.
- O processo de compilação acontece nos servidores do GitHub. Não precisa instalar Android Studio no celular.
