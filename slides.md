# Automation Enablement

* [Prerequisties](#/1)
* [Development Environments - (On Boarding)](#/2)
* [Source of Truth (GitHub)](#/3)
* [Introduction to Docker Containers](#/4)
* [Python Basics](#/5)
* [ATC Automation Platform](#/6)
* [Automating in the ATC](#/7)

---

## Prerequisties

[<](#/)

* Install Visual Studio Code\
https://code.visualstudio.com/

* Install Docker Desktop\
https://docs.docker.com/desktop/

* Install Git Client\
https://git-scm.com/downloads/

---

## Development Environments - (On Boarding)

[<](#/)

* [IDE - Visual Studio Code](#/8)
* [Python Virtual Environments](#/9)
* Visual Studio integrations and plugins – market place

---

## Source of Truth (GitHub / GitLab)

[<](#/)

* Source Control
* Version Control
* Branching
* Intro to GitLab (why / why not)

---

## Introduction to Docker Containers

[<](#/)

* Fundamentals
* IDE (Visual Studio) Integration

---

## Python Basics

[<](#/)

* Fundamentals
* Network interaction (ssh, scp, etc) - ex. netmiko
* Network automation - ex. napalm
* Automation framework - ex. nornir

---

## ATC Automation Platform

[<](#/)

* Ansible (RedHat) - Tower
* Terraform (Hashi) - TFE

---

## Automating in the ATC

[<](#/)

* Admin platform
* Webhooks (Tower or TFE API)
* Git Version Control - WWT Platform Caching
* Common areas to organize and collaborate automation and libraries - ex. Github Teams

---

## IDE - Visual Studio Code

![pete](img/8ce2473ed6df904159561876125fd6ef.png)


---

## Python Virtual Environments

![session1](sessions/session1.md)

---

## Visual Studio integrations and plugins – market place

<section>
  <pre><code data-trim data-noescape>
(def lazy-fib
  (concat
   [0 1]
   ((fn rfib [a b]
        (lazy-cons (+ a b) (rfib b (+ a b)))) 0 1)))
  </code></pre>
</section>