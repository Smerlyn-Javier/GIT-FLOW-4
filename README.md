# GitFlow4code

Esta extensión agrega soporte para la estrategia de ramificación de características descrita aquí en el modelo de ramificación de Vincent Driessen . La implementación utilizada por esta extensión es similar a la funcionalidad ofrecida por git-flow (Edición AVH) .

## Empezamos con las configuraciones basicas

### Acceso a los comandos de gitflow4code

Desde la paleta de comandos, escriba GitFlow para filtrar los comandos de GitFlow, Para abrir la paleta de comandos de vscode:

* Mac **Comando + P**
* Windows **CTRL + P**

![alt text](http:raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishFeature.png)

## Inicializar
Elija el comando Inicializar repositorio de la lista de comandos disponibles de gitflow4code.

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/Initialize-Command.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación.

**Atajos para inicializar el comando**
* ⌥⌘ / i en Mac
* Ctrl + Alt + / i en Windows


## Inicializar con la configuración predeterminada

Optar por Initialize with default(es decir master, develop, feature/, release/, y hotfix/)


![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/InitializeWithDefault.png)


## Inicializar con ajustes de configuración personalizados

Elija Initialize with custom valuesay luego especifique los valores solicitados

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/DevelopBranch.png)
![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/DevelopBranch.png)
![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FeatureBranch.png)
![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/ReleaseBranch.png)
![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/HotfixBranch.png)

Estas configuraciones se almacenan y se pueden editar en cualquier momento volviendo a ejecutar los comandos anteriores o editando en el archivo de configuración.

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/InitializeSettings.png)

## Cosas a tomar en cuenta a la hora de trabajar con git flow

## Función de inicio

Elija el Start Featurecomando de la lista de comandos disponibles de gitflow4code

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartFeature-Command.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para iniciar el comando de función

* ⌥⌘ / f en Mac
* Ctrl + Alt + / f en Windows

Si crea una rama de características fuera de su rama de desarrollo, elija Start Feature from <develop>(donde developestá el nombre de lo que elija para inicializar su rama de desarrollo)

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartFeatureDevelop.png)

o 

Si crea una rama de entidad desde otra rama base, elija Start Feature from another base branch

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartFeatureBase.png)

Luego, proporcione el nombre de la rama de su característica, y la herramienta le agregará el prefijo con el nombre que elija para las ramas de la característica.

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FeatureName.png)

## Característica de acabado

Cuando termine con su función, elija el Featurescomando de la lista de comandos disponibles de gitflow4code y luego elijaFinish Feature

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishFeature.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para finalizar el comando de función

* ⌥⌘ / ⌘f en Mac
* Ctrl + Alt + / Ctrl + f en Windows

O use el botón Finalizar función en la barra de estado

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishFeature-Statusbar.png)

# Lanzamientos

## Iniciar lanzamiento

Elija el Releasescomando de la lista de comandos disponibles de gitflow4code

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartRelease-Command.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para iniciar el comando de lanzamiento

* ⌥⌘ / r en Mac
* Ctrl + Alt + / r en Windows

Si crea una rama de lanzamiento fuera de su rama de desarrollo, elija Start Release from <develop>(dónde developestá el nombre de lo que elija para inicializar su rama de desarrollo)

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartReleaseDevelop.png)

 o 

Si crea una rama de lanzamiento desde otra rama base, elija Start Release from another base branch

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartReleaseBase.png)

Luego proporcione el nombre de su rama de lanzamiento, y la herramienta lo agregará como prefijo con el nombre que elija para sus ramas de lanzamiento

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/ReleaseName.png)

### Finalizar lanzamiento

Cuando termine con su lanzamiento, elija el Releasescomando de la lista de comandos disponibles de gitflow4code y luego elijaFinish Release

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishRelease.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para finalizar el comando de liberación
* ⌥⌘ / ⌘r en Mac
* Ctrl + Alt + / Ctrl + r en Windows

O use el botón Finalizar liberación en la barra de estado

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishRelease-Statusbar.png)

Luego proporcione el nombre de Tag esta versión

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/TagRelease.png)

## Revisiones

### Iniciar revisión

Elija el Hotfixescomando de la lista de comandos disponibles de gitflow4code

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartHotfix-Command.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

## Atajos para iniciar el comando de revisión

* ⌥⌘ / h en Mac
* Ctrl + Alt + / h en Windows

Si crea una rama de revisión fuera de su rama de producción, elija Start Hotfix from <master>(dónde masterestá el nombre de lo que elija para inicializar su rama de producción)

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartHotfixMaster.png)

o 

Si crea una rama de revisión de otra rama base, elija Start Hotfix from another base branch

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/StartHotfixBase.png)

Luego, proporcione el nombre de su rama de revisión, y la herramienta lo colocará como prefijo con el nombre que elija para ser el nombre de sus ramas de revisión

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/HotfixName.png)

## Terminar revisión

Cuando termine con su revisión, elija el Hotfixescomando de la lista de comandos disponibles de gitflow4code y luego elijaFinish Hotfix

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishHotfix.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para finalizar el comando de revisión
* ⌥⌘ / ⌘h en Mac
* Ctrl + Alt + / Ctrl + h en Windows

O use el botón Finalizar revisión en la barra de estado

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/FinishHotfix-Statusbar.png)

Luego proporcione el nombre de Tag este hotfix

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/TagHotfix.png)

### Estado de Git

Al elegir esto de la lista de comandos de gitflow4code, se mostrará el estado actual del repositorio local de git (igual que si se ejecutara git statusen la línea de comandos) y se muestra en el OUTPUTpanel

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/GetStatus-Command.png)

Alternativamente, puede usar las teclas de acceso directo que se enumeran a continuación

### Atajos para iniciar el comando de revisión

* ⌥⌘ / s en Mac
* Ctrl + Alt + / s en Windows

![alt text](https://raw.githubusercontent.com/shaggy13spe/gitflow4code/master/images/GetStatus-Result.png)