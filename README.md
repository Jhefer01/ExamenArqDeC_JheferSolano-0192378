# Examen Final Arquitectura de Computadores

## Objetivo

Desplegar una instancia EC2 en AWS utilizando CloudFormation y GitHub Actions.

## Tecnologías utilizadas

- AWS EC2
- AWS CloudFormation
- GitHub Actions
- Git
- Git Flow

## Deploy

El workflow deploy.yml crea automáticamente la infraestructura en AWS utilizando CloudFormation.

## Destroy

El workflow destroy.yml elimina automáticamente el stack creado y todos los recursos asociados.

## Template EC2

El template ec2.yaml crea:

- Una instancia Amazon Linux
- Un Security Group
- Acceso HTTP por el puerto 80
- Una página web personalizada con HTML, CSS y JavaScript

## Estudiante

Nombre: Jhefer Solano

Código: 0192378