# Guión Panel Magma 2014

> Lucharan de dos a tres caídas sin limite de tiempo!

El primer panel Magma será un evento espectacular AAA presenta.

Edwin "el ardilla" Emberosio Cruz.
Paco "Angularcito" Viramontes

Referi por el lado de los Grandes Técnicos:
Fede "Gran Scripto" Soria

VS

Manuel "El Gran Omakase" Vidaurre 
Javier "Pjax" Cervantes

Referi por el lado de los RUDOs (Ruby DOminates):
Ismael "Multi Rules" Marin

Por el titulo super "Geek"

(comentario general. Si hacemos slides hay que hacerlos en Inglés y que el panel sea en Español. Como ven?)

## Caracteríticas y Ventajas

### Arquitectura
#### Single-Page Application (SPA)
#### Multi-Page Web Applications (MPA)

### SEO

### Persistencia de datos

#### REST

#### Multiple recursos a la vez

#### Bulk Update

### Historial (del browser)

### Uso "offline"

### Session

### Escalabilidad

### Compatibilidad con browsers

### Consumo en dispositivos moviles y otros

## Uso

### Debugging

### Tracking errors en modo producción

### Madurez/Ecosystem

### Comunidad

### Infraestructura

### Deployment

### Curva de aprendizaje

## Futuro

### ReactJS

### Pjax

### Turbolinks

### El punto medio

# CAIDAS

## Primera
### Arquitecture:  API + JS Thick client (Techs Paco) vs Full Rails MVC (Rudos Javier)

* Los servicios en una API se pueden separar y escalar mas rapido y con menos costo a largo plazo.
* A corto plazo una app full Rails stack es mucho mas rapido llegar a un MVC.
* A largo plazo una app full Rails se vuelve monolitica, dificil de mantener y escalar.
* Reemplazae secciones de un API/Frontend es mas facil.
* La organizacion del trabajo puede ser mas facil en una app monolitica, no hay tanto problemas de versiones pero tambien tiene sus desventajas.
* El deployment puede ser mas fácil en una app monolítica.
* Con una app Rails clasica tienes muchas cosas resueltas que no tienes que pensar: Cookies, Seguridad etc.
* Hay mas gemas y plugins para apps vanilla Rails pero una app basada en API's tiene mucha mas flexibilidad.
* Una app monolitica tiende a hacerce lenta y hacerla mas rapida complica la arquitectura mas y mas y mas.
* El desarrollo de apps con "Thick clients" requiere de un equipo mas experimentado y tiene una curva de aprendizaje mas alta.

### HTML Render, server side (Rudos Manuel) vs client side (Techs Edwin)

* Es lento en el servidor pero ligero para los clientes.
* Hay mas problemas de compatibilidad.
* Exploradores viejos y compus lentas les cuesta mucho mas trabajo hacer el rendering del DOM.
* EL DOM ES LEEEEEENTOOOOO porque los años de falta de estandares y lo complejo de las implementaciones de CSS.
* Server side es mas para layouts sencillos sin mucha interactividad.
* Implementar cuestiones altamente interactivas con server-side rendering es incomodo, raro, monstruoso etc.
* En "client side rendering" (por lo general) se duplica logica de negocios, validaciones etc.
* La logica de negocios en un server side render acopla la vista con el modelo (por lo general).
* Realct JS rulea! (http://jlongster.com/Removing-User-Interface-Complexity,-or-Why-React-is-Awesome)

## Segunda
### BDD/TDD and Fabricates (Techs Manuel)  vs Integration with Capybara Fixtures  (Rudos PAco)
Si no hay inconveniente yo (paco) prefiero que TDD sea rudo! (26 de Mayo)
Ya no estoy tan seguro si el TDD es rudo o tecnico :S (26 de Mayo mas tarde)

* TDD esta muerto! Lo dijo DHH
* Las pruebas de integracion te dan pas por tu dinero (esfuerzo)
* Las pruebas de integracion son lentas?
* Las pruebas unitarias prueban de mas y se llenan de polvo facilmente?
* Las pruebas de integracion son "brittle"?
* "Prueba lo que tiene sentido de probar" VS "Prueba todo por si las moscas"
* Prueba pimero == "Me pongo esposas y limito mis implementaciones" 
* Prueba despues == "Mejor hagamos que esto funcione y no hay pedo porque soy un chingon"

### ActiveRecord (Rudos Javier)  vs Pure Models and DataMapper Patterns (Techs Edwin) 

## Tercera
### PaaS (heroku/[peas][peas] Rudos Javier) vs Own infrastructure in the Cloud (bare metal servers/chef/puppet Techs Edwin)
### Convensions/Defaults  (Rudos Manuel) vs Tailord made  (Techs Paco) 

* Las convensiones ayudan a la coaboracion.
* Es mas sencillo introducir gente nueva a un proyecto (Onboarding)
* Es mas facil innovar (salirse del molde) cuando la app es a la medida
* No todas las conveciones aplican para todos los proyectos
* El "boilerplate" es pura basura que alenta una aplicacion
* Una aplicacion tailor made requiere de mas atencion a cosas ya resueltas.
* Es muy facil querer reinventar la rueda todo el tiempo y por tanto perder tiempo y dinero del cliente o desarrollo de producto.
* Actualizar una app basada en convensiones es muy dificil si las API's y convensiones cambian.

## Extras
### Responsiveness vs layouts per screen size (devices)


# Logistica
## Agenda
  1. Presentación de Luchadores (1 minuto) -- Ismael hace propuesta
  1. Presentación de dinámica, app twitter, cinturon edición especial, rapada  (1 minuto) -- Fede hace propuesta
  1. Pregunta pública inicial para debate Primera Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Pregunta secreta debate Primera Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Anuncio de quien gano la Primera caida por votos en Twitter (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pregunta pública para debate Segunda Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Pregunta secreta debate Segunda Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Anuncio de quien gano la Segunda caida por votos en Twitter (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pregunta pública para debate Tercera Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Pregunta secreta debate Tercera Caida (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Pelea y respuesta de los bandos (2 minutos por bando)  -- Con el liderazgo establecido presentan su defensa
  1. Anuncio de quien gano la Tercera caida por votos en Twitter (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Preguntas y respuestas (8 minutos)   -- Responde a quien vaya dirigida la pregunta
  1. Anuncio de quien gano la Pelea con todo y las preguntas y respuestas (30 segundos)  -- Fede e Ismael se ponen de acuerdo
  1. Entrega de cinturon especial de campeones y rapado de los perdedores - barbas contra bigotes  (1 minuto)  -- Fede e Ismael se ponen de acuerdo

## Formato
  * Parados con liderazgo por tema de acuerdo a distribución y con relevo dando palmada
  * Tatuajes con tinta hena
  * Preguntas publicas conocidas con anterioridad por los bandos y las privadas son sorpresa para ellos
  * Pelearan por el cinturon edición especial de MagmaConf y barbas contra bigotes

# Preparativos
## Reuniones
### 2014-05-19
#### Asistentes
    * Fede
    * Javier
    * Paco
    * Manuel
#### Revisión y Acuerdos
  * Se reorganizaron los temas, fusionandose los más parecidos y se incluyo uno de los extras en la tercera caída.
  * Se discutió lo de si TDD debería ser Omakase o por TDD is Dead no debería ser Omakase
  * Se acordó que la rapada será de barbas y/o bigotes. Aunque sería padre llegar barbones todos

## Tareas
### 2014-05-19
  * Ismael: Presentación de Luchadores y preguntas
  * Fede: app twitter y preguntas
  * Javier, Paco, Edwin y Manuel: preparar primera caida por lo menos
  * Manuel: comunicar a Esteban sobre los requerimientos

## Agenda Proxima Reunión
### 2014-05-23
  1. Ismael: Propuesta de Presentación de Luchadores 
  1. Fede: Presentación de app twitter
  1. Ensayo de primera caida 

  [peas]: https://github.com/tombh/peas "PaaS for the People" 

## Oreguntas de los Referi
### Primer Caída
  * ¿Problemas comunes de estabilidad y mantenimiento? 
  * ¿Cuál es más rápida?

### Segunda Caída
  * ¿Realmente crees que TDD esta muerto?
  * ¿Cuando es más optima implementar alguna de estas (ActiveRecord vs DataMapper)?

### Tercer Caída
  * ¿En cuanto costos cuando es más conveniente utilizar alguna de estas?
  * ¿Cuanto tiempo comúnmente se requiere en ambas soluciones para una persona poder integrarse al código del proyecto?
