# Ejercicios de AngularJS 1.8.2

Este repositorio contiene una serie de ejercicios prácticos para aprender los conceptos fundamentales de AngularJS (versión 1.8.2). Cada archivo HTML se centra en una característica específica del framework, desde los conceptos básicos hasta temas más avanzados.

## Lista de Ejercicios

1.**[Aplicación (Lista de Compras)](1_application.html)**

    -**Descripción**: Una aplicación simple de lista de compras que permite añadir y eliminar artículos.

    -**Conceptos**: `ng-app`, `ng-controller`, `ng-model`, `ng-repeat`, `ng-click`, `ng-cloak`.

2.**[Módulos y Servicios](2_modules.html)**

    -**Descripción**: Muestra cómo definir un módulo, un servicio y un controlador, y cómo inyectar el servicio en el controlador para compartir datos.

    -**Conceptos**: `angular.module`, `app.controller`, `app.service`.

3.**[Expresiones](3_expressions.html)**

    -**Descripción**: Demuestra el uso de expresiones de AngularJS para mostrar datos numéricos, de cadena, objetos y arrays. También introduce `ng-init`.

    -**Conceptos**: `{{ expression }}`, `ng-init`.

4.**[Controladores](4_controllers.html)**

    -**Descripción**: Explica cómo definir un controlador y adjuntar propiedades y métodos al `$scope` para interactuar con la vista.

    -**Conceptos**: `ng-controller`, `$scope`, métodos en el scope.

5.**[Scope](5_scope.html)**

    -**Descripción**: Ilustra que cada controlador tiene su propio `$scope`, creando un límite de aislamiento entre ellos.

    -**Conceptos**: Aislamiento del `$scope`.

6.**[Modelos](6_models.html)**

    -**Descripción**: Muestra el uso de la directiva `ng-model` para lograr el enlace de datos bidireccional (two-way data binding) con un campo de entrada.

    -**Conceptos**: `ng-model`.

7.**[Enlace de Datos (Data Binding)](7_data_binding.html)**

    -**Descripción**: Un ejemplo claro y sencillo de enlace de datos bidireccional entre un campo de entrada y una expresión en la vista.

    -**Conceptos**: `ng-model`, `{{ expression }}`.

8.**[Manipulación del DOM](8_html_dom.html)**

    -**Descripción**: Demuestra cómo manipular el DOM de forma declarativa utilizando directivas como `ng-class` y `ng-click` para cambiar estilos dinámicamente.

    -**Conceptos**: `ng-class`, `ng-click`.

9.**[Filtros](9_filters.html)**

    -**Descripción**: Muestra cómo usar filtros incorporados (`uppercase`) y cómo crear filtros personalizados para transformar los datos en la vista.

    -**Conceptos**: `filter`, `app.filter`.

10.**[Eventos](10_events.html)**

    -**Descripción**: Explica cómo manejar eventos del DOM, como clics de botón, utilizando la directiva `ng-click`.

    -**Conceptos**: `ng-click`.

11.**[Formularios](11_forms.html)**

    -**Descripción**: Demuestra la validación de formularios, mostrando mensajes de error basados en el estado del formulario (`$valid`, `$submitted`, `$dirty`, `$error`).

    -**Conceptos**: `ng-submit`, `novalidate`, validación de formularios.

12.**[Inclusión de Vistas (ng-include)](12_include.html)**

    -**Descripción**: Muestra cómo incluir plantillas HTML externas o en línea de forma condicional usando `ng-include` y el servicio `$sce` por seguridad.

    -**Conceptos**: `ng-include`, `$sce`, `text/ng-template`.

13.**[Servicio $http](13_http.html)**

    -**Descripción**: Explica cómo realizar solicitudes HTTP (GET) a una API para obtener datos y mostrarlos en la vista, manejando tanto el éxito como el error.

    -**Conceptos**: `$http.get`.

14.**[API y Directivas](14_api.html)**

    -**Descripción**: Un ejemplo más del uso de `$http` para obtener una lista de datos y mostrarla con `ng-repeat`. También introduce una directiva personalizada simple.

    -**Conceptos**: `$http`, `ng-repeat`, `app.directive`.

15.**[Enrutamiento (Routing)](15_routing.html)**

    -**Descripción**: Demuestra cómo configurar el enrutamiento del lado del cliente utilizando el módulo `ngRoute` para crear una aplicación de una sola página (SPA).

    -**Conceptos**: `ngRoute`, `ng-view`, `$routeProvider`.

16.**[Animaciones](16_animation.html)**

    -**Descripción**: Muestra cómo usar el módulo `ngAnimate` para agregar animaciones CSS a directivas como `ng-hide`, mejorando la experiencia del usuario.

    -**Conceptos**: `ngAnimate`, animaciones CSS con clases `ng-hide`.
