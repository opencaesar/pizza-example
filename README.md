# Pizza Example

This project demonstrates a simple [OML](http://www.opencaesar.io/oml/) model from the pizza domain. For details, follow this [tutorial](http://www.opencaesar.io/oml-tutorials/#tutorial1).

## Clone
```
  git clone https://github.com/opencaesar/pizza-example.git
  cd sysml2
```

## Clean
```
./gradlew clean
```

## Build
```
./gradlew build
```

## Start Fuseki Server
```
./gradlew startFuseki
```

## Stop Fuseki Server
```
./gradlew stopFuseki
```

## Load to Fuseki Dataset
```
./gradlew owlLoad
```

Pre-req: A Fuseki server with a firesat dataset must be running at http://localhost:3030/firesat (see Start Fuseki above)  

## Run SPARQL Queries
```
./gradlew owlQuery
```

Pre-req: A Fuseki server with a firesat dataset must be running at http://localhost:3030/firesat (see Load to Fuseki Dataset)  
