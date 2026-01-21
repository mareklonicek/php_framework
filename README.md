# 💎 My Custom PHP Framework

<p align="center">
  <img src="public/assets/php_fram_logo.png" width="1200" alt="Framework Icon">
</p>

<p align="center">
  <b>Personal custom PHP framework</b><br>
  Experimental • Educational • From scratch
</p>

---

## 📌 About

This is my **personal custom PHP framework**, built for **learning, testing, and experimenting** with core backend concepts.

<table>
<tr>
<td>

### 🎯 Goals
<ul>
  <li>Understand PHP internals</li>
  <li>Build MVC architecture</li>
  <li>Custom Routing & DI container & Middelware & Authentication</li>
  <li>No heavy frameworks</li>
</ul>

</td>
<td>

### ⚠️ Status
<ul>
  <li>Not production-ready</li>
  <li>Breaking changes allowed</li>
  <li>Refactoring playground</li>
</ul>

</td>
</tr>
</table>

---

## 🧱 Architecture

<ul>
  <li>📦 Core
    <ul>
      <li>🔀 Router</li>
      <li>🎮 Controller</li>
      <li>🧩 Dependency Injection</li>
    </ul>
  </li>
  <li>🖼️ MVC
    <ul>
      <li>📄 Models</li>
      <li>🧠 Business Logic</li>
      <li>🎨 Views</li>
    </ul>
  </li>
</ul>

---

## 🛠️ Tech Stack

<table>
<tr><th>Layer</th><th>Technology</th></tr>
<tr><td>Backend</td><td>PHP 8+</td></tr>
<tr><td>Frontend</td><td>HTML5, CSS3</td></tr>
<tr><td>Versioning</td><td>Git</td></tr>
</table>

---

## 📂 Project Modular Approach

```
Framework
 ├─ Core
 │   ├─ Router
 │   ├─ Container
 │   └─ Kernel
 ├─ App
 │   ├─ Model
 │   ├─ View
 │   └─ Controller
 └─ Public
     ├─ index.php
     └─ assets
```
## Project Folders & Files Tree Structure

```
├── 📁 Core
      ├── 📄 App.php
      ├── 📄 Authenticator.php
      ├── 📄 Container.php
      ├── 📄 Database.php
      ├── 📁 Middleware
            ├── 📄 Authenticated.php
            ├── 📄 Guest.php
            └── 📄 Middleware.php
      ├── 📄 Response.php
      ├── 📄 Router.php
      ├── 📄 Session.php
      ├── 📄 ValidationException.php
      ├── 📄 Validator.php
      └── 📄 functions.php
├── 📁 Http
      ├── 📁 Forms
            └── 📄 LoginForm.php
      └── 📁 controllers
            ├── 📄 about.php
            ├── 📄 contact.php
            ├── 📄 index.php
            ├── 📁 notes
                  ├── 📄 create.php
                  ├── 📄 destroy.php
                  ├── 📄 edit.php
                  ├── 📄 index.php
                  ├── 📄 show.php
                  ├── 📄 store.php
                  └── 📄 update.php
            ├── 📁 registration
                  ├── 📄 create.php
                  └── 📄 store.php
            └── 📁 session
                  ├── 📄 create.php
                  ├── 📄 destroy.php
                  └── 📄 store.php
├── 📄 bootstrap.php
├── 📄 composer.json
├── 📄 composer.lock
├── 📄 config.php
├── 📄 info.txt
├── 📄 phpunit.xml
├── 📁 public
      ├── 📁 assets
            └── 📄 php_fram_logo.png
      ├── 📄 index.php
      └── 📄 playground.php
├── 📄 routes.php
├── 📁 tests
      ├── 📁 Feature
            └── 📄 ReferralTest.php
      ├── 📄 Pest.php
      ├── 📄 TestCase.php
      └── 📁 Unit
            ├── 📄 ContainerTest.php
            └── 📄 ValidatorTest.php
├── 📁 views
      ├── 📄 403.php
      ├── 📄 404.php
      ├── 📄 about.view.php
      ├── 📄 contact.view.php
      ├── 📄 index.view.php
      ├── 📁 notes
            ├── 📄 create.view.php
            ├── 📄 edit.view.php
            ├── 📄 index.view.php
            └── 📄 show.view.php
      ├── 📁 partials
            ├── 📄 banner.php
            ├── 📄 footer.php
            ├── 📄 head.php
            └── 📄 nav.php
      ├── 📁 registration
            └── 📄 create.view.php
      └── 📁 session
            └── 📄 create.view.php

