# Great Sage - Rimuru Tempest (esqueleto 0.1)
Forge 1.20.1 (47.3.0), Java 17.
Build: `./gradlew build` (gere o wrapper com `gradle wrapper`). Teste: `./gradlew runClient`.
NAO COMPILADO/TESTADO ainda. Feito: tela Grande Sabio (abas, busca, favoritos, paginacao), keybinds (Mouse4 / M).
Falta: HUD, absorcao, dados do jogador, rede, adaptador do Jujutsu Craft (precisa do JAR).

## Gerar o .jar
Local: instale o JDK 17 e o Gradle 8.1.1 e rode `gradle build`. O JAR sai em `build/libs/`.
Sem instalar nada: suba esta pasta para um repositorio no GitHub; a aba Actions gera o JAR (artifact "greatsage-jar").
Coloque o JAR na pasta mods junto com Jujutsu Craft, GeckoLib e playerAnimator.
