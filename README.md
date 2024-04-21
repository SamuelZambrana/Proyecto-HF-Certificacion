# Proyecto-HF-Certificacion

Este es un proyecto increíble que aborda una red de mercado donde tenemos toda la trazabilidad del producto. Aquí, los usuarios pueden encontrar información útil sobre cómo usarlo y contribuir.

## ¿Qué hace el proyecto?

La empresa Merca-link, dedicada a la venta al por menor de alimentos, productos de
limpieza e higiene personal y enseres, se encuentra implementando una red
Blockchain para dotar de las más altas cotas de trazabilidad a los productos de su
marca blanca: “Haciendo”.

## Cómo comenzar

Entra en la carpeta raíz del proyecto y descarga los binarios de HF:
curl -sSLO
https://raw.githubusercontent.com/hyperledger/fabric/main/scri
pts/install-fabric.sh && chmod +x install-fabric.sh
./install-fabric.sh b
Otras operaciones
Así puedes levantar la red e instalar el contrato inteligente:
./network.sh up createChannel -ca
./network.sh deployCC -ccn merca-chaincode -ccl javascript
-ccv 1.0.0 -ccp ../merca-chaincode
Así puedes parar y borrar la red:
./network.sh down
No dudes en levantar y parar la red tantas veces como necesites a lo largo de la
práctica.

## ¿Necesitas ayuda?

Si tienes alguna pregunta o necesitas ayuda, no dudes en abrir un **issue** o ponerte en contacto conmigo.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas contribuir, sigue estos pasos:

1. Haz un **fork** de este repositorio.
2. Crea una nueva rama con un nombre descriptivo.
3. Realiza tus cambios y envía un **pull request**.

## Mantenimiento

Este proyecto está mantenido por SamuelZambrana.
