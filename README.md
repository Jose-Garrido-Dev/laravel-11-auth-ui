<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Instalación de Auth con bootstrap

# PHP artisan migrate

Descargamos package de auth de ui
https://github.com/laravel/ui

# Lo instalamos: 

` composer require laravel/ui   `

# Luego:

 ` php artisan ui bootstrap --auth  `

Preguntará e indicará que el controlador existe si desea reemplazarlo, seleccionamos si

# Luego:

 ` npm install  `



 Ya con eso funciona nuestra autenticación.
 
 pero tendremos un detalle al loguearse volver al menú en la vista welcome debemos modificar arriba donde dice dashboard ya que dará error 404 si estamos logueados
 modifcar por 


 ` href="{{ url('/home') }}"   `
