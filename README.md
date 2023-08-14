# Trabajo Practico Final Criptografia y Blockchain


El siguiente trabajo practico usara como base los repositorios [lambdaworks](https://github.com/lambdaclass/lambdaworks) y [Starknet Stack Prover Lambdaworks](https://github.com/lambdaclass/starknet_stack_prover_lambdaworks)

De ahi vamos a sacar la logica necesaria para el verifier.


Una descripcion mas detallada del trabajo se encuentra en nuestro Notion [aca](https://mis-notas.notion.site/Final-30a1521f0d21498f8ce5488b549103da?pvs=4)

# Ejecutar

## Parte 1

Correr 

`cargo run`

Para correr el archivo [main.rs](./src/main.rs)

## Parte 2

Usando Docker

Paso 1) 

`make docker_build_cairo_compiler`

Paso 2)

`make docker_compile_and_run_all PROGRAM=cairo_programs/exercise_2.cairo`

## Parte 3

[Diagrama de Flujo](https://www.notion.so/mis-notas/Parte-3-23af68d503064bfd932181469313fdbb?pvs=4#c87d49ffb9a842bc8e76d683e444443d)

## Parte 4
Los parametros `Queries` y `Blowup-factor` son importantes para la seguridad del prover pero tenemos que tomar un tradeoff entre el largo de la prueba y el tiempo que tarda en generarse para que nos sea util. Ver [aca](https://mis-notas.notion.site/Parte-4-cbe2522f258145a091c816bd2d2efc39?pvs=4)

## Parte 5
Los parametros principales son `Queries` y `Blowup-factor`. Una explicacion mas detallada se encuentra [aca](https://mis-notas.notion.site/Parte-5-56e84d86abd54b10bfaf6c5ddebf43d5?pvs=4)

## Parte 6
Desarrollo [aca](https://mis-notas.notion.site/Parte-6-64df88e05a944d179fb9e27707536686?pvs=4)

# Integrantes

[Luis Paredes](https://github.com/LuisParedes1) 104851 lparedesr@fi.uba.ar

[Nicole Raveszani](https://github.com/nravesz) 100193 nraveszani@fi.uba.ar
