# PresTech - BackEnd
## 🚀 Descripción del Proyecto
Este repositorio contiene el código fuente del BackEnd para el sitio web de PresTech. Es la capa de servicios y lógica de negocio responsable de gestionar la información, la autenticación de usuarios y la comunicación con la base de datos para la aplicación web.

El objetivo principal es proporcionar una API robusta y escalable para que el FrontEnd (sitio web de PresTech) pueda interactuar de manera eficiente.

## 💻 Tecnologías Utilizadas
El proyecto fue desarrollado utilizando el ecosistema de Microsoft .NET, lo que garantiza un rendimiento óptimo y un desarrollo estructurado.

Lenguaje: C#

Framework: .NET / ASP.NET Core (Asumido por el uso de C# y ser un Backend web moderno)

Gestión de Dependencias: NuGet

Base de Datos: MySQL

ORM (Mapeo Objeto-Relacional): Entity Framework Core

## ⚙️ Configuración e Instalación
Sigue estos pasos para obtener una copia operativa del proyecto en tu máquina local con fines de desarrollo y pruebas.

Requisitos Previos
Asegúrate de tener instalado lo siguiente:

.NET SDK: Versión 9.0 o superior.

IDE: Visual Studio

Base de Datos: MySQL descargado

## Pasos de Instalación
Clonar el Repositorio:

```bash
   git clone https://github.com/JorgeIRamos/PresTech-BackEnd.git
   cd PresTech-BackEnd/PresTechBackEnd
   ```

Restaurar Dependencias: Ejecuta el siguiente comando para descargar todos los paquetes NuGet necesarios:

```bash
    dotnet restore
   ```

Aplicar Migraciones para crear la estructura de la base de datos:

```bash
    dotnet ef database update
   ```

## ▶️ Ejecución del Proyecto
Una vez configurado, puedes ejecutar el backend desde tu terminal:

Navega a la carpeta principal del proyecto:

```bash
    cd PresTech-BackEnd/PresTechBackEnd
   ```


Ejecutar la Aplicación:

```bash
    dotnet run
   ```
La API estará disponible en la URL especificada en la configuración.

## 👨‍💻 AUTORES

Jorge Iván Ramos Murgas
