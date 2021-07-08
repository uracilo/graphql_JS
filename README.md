# GraphQL Express JS

## Start project 

```
npm start
```

- Query to put a new Client


```
mutation{
  addCliente(nombre:"Benjamin",telefono:"12312312313"){
    id
    nombre
    telefono
  }
}
```
- Query to get all clients with name and id

```
{
  clientes{
    id
    nombre
  }
}
```
