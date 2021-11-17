<div class="grid__item width-4-12 hide-mobile toc" markdown="1">
## Table of Contents
### Getting Started

 - [Java SDK](#java-sdk)
 - [Java JRE](#java-jre)
 - [Maven 2.2.1](#maven-221)
 - [Maven 3.0.4](#maven-304)
 - [Ant](#ant)
 - [Eclipse 4.5 Java EE IDE](#eclipse-45-java-ee-ide)
 - [Angular](#angular)
 - [Quick Start Pet Shop POC](#quick-start-pet-shop-poc)

### Guides

 - [Get More Guides]({{site.baseurl}}/guides)

</div>

<div class="grid__item width-8-12 width-12-12-m gs-content">

<div markdown="1">
## Java SDK

Installazione:
- Copiare le cartelle presenti in **\\\Nas\Install\Strumenti di sviluppo\jdk** in **D:\Programmi\java**. 
</div>

<div markdown="1">
## Java JRE

Installazione:
- Eseguire il file **\\\Nas\Install\Strumenti di sviluppo\Java\jre-6u21-windows-i586-s.exe**.

- Se viene chiesto di reinstallare il software, premere Si.

- Spuntare la casella Cambia la cartella di destinazione.

- Premere Installa >.

- Premere Cambia….

- Impostare la cartella **D:\Programmi\java\jre6** e premere OK.

- Premere Avanti >.

- Al termine, premere Chiudi.
</div>

<div markdown="1">
## Maven 2.2.1

Installazione:
- Estrarre il contenuto del file **\\\Nas\Install\Strumenti di sviluppo\Maven\apache-maven-2.2.1-bin.zip** in **D:\Programmi**.

Configurazione
- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Maven\mvn.bat** in **D:\Programmi\apache-maven-2.2.1\bin** sovrascrivendo il file esistente.

- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Maven\settings.xml** in **D:\Programmi\apache-maven-2.2.1\conf** sovrascrivendo il file esistente. 
</div>

<div markdown="1">
## Maven 3.0.4

Installazione
- Estrarre il contenuto del file **\\\Nas\Install\Strumenti di sviluppo\Maven\3.0.4\apache-maven-3.0.4-bin.zip** in **D:\Programmi**.

Configurazione
- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Maven\3.0.4\mvn.bat** in **D:\Programmi\apache-maven-3.0.4\bin** sovrascrivendo il file esistente.

- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Maven\3.0.4\mvn7.bat** in **D:\Programmi\apache-maven-3.0.4\bin**.

- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Maven\3.0.4\settings.xml** in **D:\Programmi\apache-maven-3.0.4\conf** sovrascrivendo il file esistente. 

- Modificare la variabile di ambiente PATH ed aggiungere **D:\Programmi\apache-maven-3.0.4\bin**.

- Aggiungere ed impostare le seguenti variabili di ambiente:
    - **M2_HOME**: D:\Programmi\apache-maven-3.0.4
    - **M2_REPO**:  D:\m2-repository
    - **MAVEN_OPTS**: -Xmx1024m

</div>

<div markdown="1">
## Ant

Installazione
- Estrarre il contenuto del file **\\\Nas\Install \Strumenti di sviluppo\Ant\apache-ant-1.6.5-bin.zip** in **D:\Programmi**.

Configurazione
- Copiare il file **\\\Nas\Install\Strumenti di sviluppo\Ant\and.bat** in **D:\Programmi\apache-ant-1.6.5\bin** sovrascrivendo il file esistente.

- Modificare la variabile di ambiente PATH ed aggiungere **D:\Programmi\apache-ant-1.6.5\bin**.

- Aggiungere la variabili di ambiente **ANT_OPTS** ed impostarla a -Xmx1024m.
</div>


<div markdown="1">
## Eclipse 4.5 Java EE IDE

- Installazione e configurazione dell'ambiente.

- Installazione dei plugin necessari.

- configurazione della JDK o JRE java in Eclipse.

<a href="{{site.baseurl}}/guides/getting-started" class="button-cta secondary">LEGGI LA GUIDA</a>
</div>

<div markdown="1">
## Angular

- Installazione e configurazione dell'ambiente e dell'IDE.

- Installazione dei plugin necessari e quelli opzionali ma che migliorano il lavoro.

- Sviluppo dei test.

- Istuzioni su come far partire il progetto.

<a href="{{site.baseurl}}/guides/angular" class="button-cta secondary">LEGGI LA GUIDA</a>
</div>

<div markdown="1">
## Quick Start Pet Shop POC

- Installazione e configurazione dell'ambiente e dell'IDE.

- Installazione dei plugin necessari e quelli opzionali ma che migliorano il lavoro.

- Sviluppo dei test.

- Istuzioni su come far partire il progetto.

<a href="{{site.baseurl}}/guides/quick-start-pet-shop-poc" class="button-cta secondary">LEGGI LA GUIDA</a>
</div>







<!-- <div class="guide-item" markdown="1">
## Getting Started with Reactive

Learn how to create a reactive application with Quarkus and explore the different reactive features offered by Quarkus.
This guide covers:

* A quick glance at the Quarkus engine and how it enables reactive
* A brief introduction to Mutiny - the reactive programming library used by Quarkus
* Bootstrapping a reactive application
* Creating a reactive JAX-RS endpoint (asynchronous, streams...)
* Using reactive database access
* Interacting with other reactive APIs

<a href="{{site.baseurl}}/guides/getting-started-reactive" class="button-cta secondary">READ THE GUIDE</a>
</div> -->

<div class="guide-item" markdown="1">
## Quickly Bootstrap Your Application

With <a href="https://code.quarkus.io">code.quarkus.io</a>, in a few clicks, you can bootstrap your Quarkus application and discover its extension ecosystem.

Explore the wide breadth of technologies Quarkus applications can be made with.

<a href="https://code.quarkus.io" class="button-cta secondary">START CODING</a>
</div>

<!-- <div class="guide-item" markdown="1">
## Building Native Executables

This guide covers:
- Compiling the application to a native executable
- The packaging of an application in a Docker container

This guide requires:
- Completion of the [Creating Your First Application]({{site.baseurl}}/guides/getting-started) guide

<a href="{{site.baseurl}}/guides/building-native-image" class="button-cta secondary">READ THE GUIDE</a>
</div> -->

<!-- <div class="guide-item" markdown="1">
## Using our Tooling

Quarkus comes with a toolchain enabling developers from live reload all the way down to deploying a Kubernetes application.
In this guide, we will explore:

* how to use Maven as a build tool
* how to use Gradle as a build tool
* how to use the native CLI for your toolchain (coming soon)
* how to create and scaffold a new project
* how to deal with extensions
* how to enable live reload
* how to develop your application in your IDE
* how to compile your application natively

<a href="{{site.baseurl}}/guides/tooling" class="button-cta secondary">READ THE GUIDE</a>
</div> -->

</div>
