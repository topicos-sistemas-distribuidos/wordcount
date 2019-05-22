# wordcount
Wordcount using hadoop

Features
---
1. Faz a contagem de palavras de arquivos texto de uma pasta

Roteiro de execução
---
Faça a configuração do Cluster do Hadoop com 3 nós usando containers Docker disponível em https://github.com/topicos-sistemas-distribuidos/hadoop-cluster-docker

1. Vá até o nó master do hadoop. 

Obs: Inicie o hdfs e o yarn. É preciso garantir que o nó master tenha instalado o git, o maven e um editor de texto.  

2. Execute um maven clean
```
$ mvn clean
```

3. Execute um maven compile
```
$mvn compile
```

4. Execute um maven package
```
$mvn package
```

5. Execute o script my-wordcount.sh
```
$./my-wordcount.sh
```

O output deverá ser uma lista contendo palavra e quantas vezes ela apareceu no texto. 
