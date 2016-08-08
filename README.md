# Integración de OpenStack con un Directorio Activo

## ¿Qué puedo encontrar aquí?

Este repositorio contiene documentación sobre cómo realizar de forma exitosa la integración de OpenStack con un Directorio Activo.

Este proyecto fue presentado como Trabajo Fin de Grado en la Universidad de Oviedo en julio de 2015.

### Resumen

Este proyecto cubrirá la documentación e instalación desde cero de la infraestructura necesaria para desplegar un sistema de computación privada en la nube, basado en tecnologías OpenStack. Como particularidad adicional, todos los usuarios del mismo serán almacenados y gestionados desde una herramienta externa a este sistema de nube.

Para llevarlo a cabo además del ya mencionado software de computación en la nube, se realizarán todas las configuraciones necesarias para disponer de un sistema de
autenticación basado en la implementación de Microsoft del protocolo LDAP, llamado comercialmente Directorio Activo.

Los usuarios y sus credenciales serán almacenados de forma centralizada en el servidor Windows y ambos sistemas serán configurados para realizar una integración con el agente encargado de la autenticación en OpenStack.

Con esto, usuarios almacenados y gestionados desde un ente externo y desconocido para OpenStack como es el Directorio Activo, podrán acceder y utilizar los recursos disponibles en la nube.

### Summary

The aim of this project is to cover the installation and documentation process of all of the infrastructure needed to deploy a private cloud based on OpenStack technologies. In addition to this, all the users of the system will be stored and managed from an external tool not initially related to OpenStack.

In order to make this possible, an authentication system based on Microsoft technologies will be also be deployed and configured. This project will use Microsoft Active Directory as the element that interacts with the OpenStack Identity provider.

Therefore, users and passwords will be kept on the Windows side and both systems will be configured to communicate and trust each other. Thanks to this, users stored and managed from an external element will be able to login and use the available resources in the deployed OpenStack private cloud.

## Documentos

* [Documentación Final formato PDF](https://github.com/danifr/tfg/blob/master/docs/Documentacion%20Final.pdf)
* [Documentación Final formato ODT](https://github.com/danifr/tfg/blob/master/docs/Documentacion_plantilla.odt)
* [Presentación Final](http://slides.com/dafero/deck#/) (alojada en slides.com)
