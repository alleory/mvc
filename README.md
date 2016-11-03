# Mini - MVC

1. В настройках константа LAYOUT определяет шаблон для всего приложения.
2. Но также мы легко можем переопределить шаблон для конкретной страницы, указав новое значение свойства $this->layout в нужном экшене.
3. Также мы можем переопределить шаблон для всего контроллера, переопределив в контроллере значение public $layout = 'другой шаблон'. Это нужно в том случае, если все экшены контроллера будут использовать другой шаблон, чтобы сделать это один раз в контроллере, а не каждый раз в каждом экшене.
Итого, мы можем: определять шаблон в настройках фреймворка, определять его для конкретной страницы и определять его сразу для группы страниц (в контроллере).﻿