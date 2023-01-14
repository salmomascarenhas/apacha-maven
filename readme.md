# Estudos apache maven
Repositório utilizado para documentar estudos do Apache Maven.

## Comandos úteis
Para criar um projeto utilizado algum arquétipo (template) disponível no repositório maven. 
``` mvn archetype:generate -DgroupId=br.std.study -DartifactId=quick-start-maven -Darchetype=maven-archetype-quickstart -DinteractiveMode=false ```

Compila todos os arquivos .java:
``` mvn compile ```

Roda todas as classes de testes:
``` mvn test ```

Empacota a aplicação (cria o .jar):
``` mvn package ```

Limpar o diretório de trabalho  (apagar pasta target):
``` mvn clean ```

Publica no repositório local a aplicação (para distriubuição):
``` mvn install ```

Mostra a construção do classpah de determinado escopo (test, compile, runtime, tree, analyse...):
``` mvn dependecy:build-classpath ```

Utilizar um plugin específico:
``` mvn[plugin-name]:[goal-name] ```

