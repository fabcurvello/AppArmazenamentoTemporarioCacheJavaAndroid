# App Armazenamento Temporário em Cache (Java Android)

> Repositório didático: exercício prático de Android nativo com **Java**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo que salva uma mensagem digitada pelo usuário no **cache** do aparelho e depois a recupera. Mostra na prática como usar o armazenamento temporário do Android.

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## O que o app faz

- Campo de texto para o usuário digitar uma mensagem.
- Botão **Salvar**: grava a mensagem em um arquivo (`temp_message_cache.txt`) no diretório de cache do app (`getCacheDir()`).
- Botão **Exibir**: lê o arquivo do cache e mostra a mensagem na tela.

## Conceitos trabalhados em aula

- Armazenamento temporário em **cache** com `getCacheDir()`
- Leitura e escrita de arquivos com `FileOutputStream` e `FileInputStream`
- Tratamento de exceções (`IOException`) e *try-with-resources*
- Diferença entre armazenamento em cache (pode ser limpo pelo sistema) e armazenamento interno
- Vínculo entre código e layout XML (`findViewById`) e eventos de clique

## Tecnologias

- **Java**
- **Android SDK** (Android Studio)
- **Gradle**
- `minSdk 28` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/AppArmazenamentoTemporarioCacheJavaAndroid.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 28 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [AppArmazenamentoCacheAnimaUNA](https://github.com/fabcurvello/AppArmazenamentoCacheAnimaUNA)
- [AppArmazenamentoCacheAnima](https://github.com/fabcurvello/AppArmazenamentoCacheAnima)
- [AppNotasTemporariasJava](https://github.com/fabcurvello/AppNotasTemporariasJava)
- [AppNotasTemporariasKotlin](https://github.com/fabcurvello/AppNotasTemporariasKotlin)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
