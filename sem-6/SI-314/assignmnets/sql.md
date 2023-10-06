# sql

## omowiefjoweijf

```sql
select codmascota as 'codigo de mascota', alias as 'nombre de mascota', especia, raza, color from mascotas

select count(codmascota) as çasntidad depor especia', especia from mascotas
    group by (especia)
    order by especie

select codmascota as 'codigo de mascota', alias as 'nombre de mascota', especia, raza, color from mascotas
    order by especie;

select avg(pesoactual) as 'peso promedio', especia from masctoas
    group by (especia)
    order by espeica;
    
print getdate()

/*consulta con producto cartesiano*/
select count(*) from clietnes;
select count(*) from mascotas;
select * from mastocas;

select * from clientes, mascotas
    where mascotas.codclietne = clientes.codigocli;
```

entity table
---
| mascotas | clientes | |
|----------|----------|-|
| codmascota | codigocli |
| alias | nombre |
| especie | apellido | |
| raza | direccion | |
| color | telefono | |
| pesoactual | email | |
| codcliente |  | |
---