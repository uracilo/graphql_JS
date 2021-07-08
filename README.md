




{
  clientes{
    id
    nombre
  }
}


mutation{
  addCliente(nombre:"Benjamin",telefono:"12312312313"){
    id
    nombre
    telefono
  }
}