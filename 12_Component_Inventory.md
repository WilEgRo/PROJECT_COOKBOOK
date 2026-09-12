# Component Inventory

Versión: 1.0

Estado: Aprobado

Última actualización:
17 Julio 2026

Dependencias:
11_User_Flows.md

---

# Objetivo

Definir todos los componentes reutilizables que formarán el sistema de interfaz de La Martina.

Todo elemento visual debe convertirse en un componente reutilizable.

Nunca desarrollar componentes duplicados.

---

# Filosofía

Construir una sola vez.

Reutilizar siempre.

Escalar sin romper consistencia.

---

# Estructura

Átomos

↓

Moléculas

↓

Organismos

↓

Templates

↓

Páginas

---

# Átomos

## Botones

Primario

Secundario

Outline

Ghost

Icon Button

Floating Button

FAB

Estados:

Default

Hover

Active

Focus

Disabled

Loading

---

## Tipografía

H1

H2

H3

H4

H5

H6

Subtitle

Body Large

Body

Small

Caption

Label

Link

---

## Inputs

Text

Password

Search

Email

Phone

Textarea

Checkbox

Radio

Switch

Select

Date

Upload

OTP

---

## Etiquetas

Badge

Chip

Tag

Status

Precio

Nuevo

Popular

Oferta

Premium

---

## Iconos

Line

Filled

Social

Acciones

Educación

Cocina

Navegación

---

# Moléculas

Campo de búsqueda

Campo de login

Tarjeta de curso pequeña

Tarjeta de artículo

Tarjeta de testimonio

Contador

Breadcrumb

Paginación

Rating

Avatar

Comentario

Notificación

Toast

Tooltip

Dropdown

Accordion

Tabs

Timeline

Progress Bar

Step Indicator

---

# Organismos

Header

Mega Menu

Hero

Grid Cursos

Slider Testimonios

Galería

FAQ

CTA

Footer

Dashboard

Sidebar

Tabla

Calendario

Formulario Contacto

Formulario Registro

Formulario Login

Formulario Compra

---

# Componentes Académicos

Card Curso

Card Instructor

Card Escuela

Card Certificado

Card Receta

Card Blog

Card Evento

Card Comunidad

Card Alumno

---

# Componentes Multimedia

Video Player

Audio Player

Galería

Carrusel

Lightbox

Visor PDF

Descargas

---

# Dashboard

Resumen

Progreso

Mis Cursos

Calendario

Notificaciones

Actividad

Certificados

Favoritos

---

# Componentes de Compra

Precio

Plan

Checkout

Resumen

Método de Pago

Cupón

Factura

---

# Componentes de Estado

Empty State

Loading

Skeleton

Error

404

500

Offline

Sin Resultados

---

# Componentes de Comunidad

Publicación

Comentario

Respuesta

Like

Compartir

Perfil

Ranking

Eventos

---

# Componentes de Administración

Tabla

Filtros

Búsqueda

Editor

Uploader

Dashboard Analytics

Gestión Usuarios

Gestión Cursos

Gestión Pagos

Gestión Certificados

---

# Convención de nombres

Componentes:

PascalCase

Ejemplo:

CourseCard

HeroSection

NavigationMenu

PrimaryButton

---

Archivos

PrimaryButton.jsx

CourseCard.jsx

DashboardSidebar.jsx

HeroPortal.jsx

---

Reglas

Un componente = una responsabilidad.

No duplicar lógica.

No repetir estilos.

Props claras.

Documentación obligatoria.

---

Checklist

✓ Reutilizable

✓ Responsive

✓ Accesible

✓ Documentado

✓ Animable

✓ Fácil mantenimiento

---

Resultado esperado

Todo el proyecto debe poder construirse reutilizando componentes sin necesidad de crear versiones diferentes del mismo elemento.