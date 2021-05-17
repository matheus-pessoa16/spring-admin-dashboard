# Dashboard de Métricas

Para executar este projeto, clone-o e abra com uma IDE que permita execução de projetos Spring.

Também é possível gerar uma arquivo .jar para execução. Os comandos são listados abaixo.

Gerando arquivo .jar
```bash
mvn clean package -DskipTests
```

Após finalização, dentro da pasta ´´´target/´´´ estarão os arquivos gerados, incluindo um jar. Execute-o com o seguinte comando

```bash
java -jar dashboard-0.0.1-SNAPSHOT.jar
```

Caso o nome seja diferente, basta trocar dashboard-0.0.1-SNAPSHOT.jar pelo nome do seu arquivo.
