## **INSTALACIÓN DE HELM**  

![helm-kubernetes](https://user-images.githubusercontent.com/72433702/152120096-5b10f944-a51e-4a63-9c54-a9debcd9220b.png) ![boat](https://user-images.githubusercontent.com/72433702/152120333-20be82fd-f28c-45c6-9b35-c9729a605405.gif)



### INSTALACIÓN EN POWERSHELL

#### **PASOS PREVIOS**

#### **Instalar CHOCOLATEY**

### INSTALACIÓN CHOCOLATEY

## 1-Abrimos PowerShell y ejecutamos los siguientes comandos:

## `Get-ExecutionPolicy`
#### Permite ver la política que tenemos, por defecto aparecerá [Restricted]

## `Set-ExecutionPolicy AllSigned`

#### Al ejecutar este comando se firmarán todas las políticas para poder instalar Chocolatey

![helm](https://user-images.githubusercontent.com/72433702/152120048-4ea9f519-9ee1-4757-a1ea-048983efd219.PNG)

## Instalación de Chocolatey

## `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))`

![helm2](https://user-images.githubusercontent.com/72433702/152120555-4b3d6e56-86d4-40da-8079-97b5110388c1.PNG)

![helm3](https://user-images.githubusercontent.com/72433702/152120901-7115d383-87d1-4783-af4e-f43ca9d4f139.PNG)

![helm4](https://user-images.githubusercontent.com/72433702/152120927-e50446d1-7176-489f-a843-44753e157956.PNG)


## INSTALACIÓN DE HELM




