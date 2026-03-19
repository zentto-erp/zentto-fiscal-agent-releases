# Zentto Fiscal Agent

Agente fiscal local para impresoras y perifericos. Se instala como servicio Windows.

## Descarga

Descarga la ultima version desde **[Releases](https://github.com/zentto-erp/zentto-fiscal-agent-releases/releases/latest)**.

- **`ZenttoFiscalAgent-Setup-vX.X.exe`** — Instalador automatico (recomendado)
- **`ZenttoFiscalAgent-Portable-vX.X.zip`** — Version portable (manual)

## Instalacion con el .exe

1. Descarga `ZenttoFiscalAgent-Setup-vX.X.exe`
2. Ejecuta como **Administrador**
3. Sigue el asistente
4. El servicio se inicia automaticamente en `http://localhost:5059`

## Instalacion manual (portable)

1. Descarga y descomprime el ZIP
2. Abre PowerShell como Administrador
3. Ejecuta: `powershell -ExecutionPolicy Bypass -File .\INSTALAR_SERVICIO.ps1`

## Verificar

Abre en el navegador: [http://localhost:5059](http://localhost:5059)

## Desinstalar

Desde "Agregar o quitar programas", o ejecutar `DESINSTALAR_SERVICIO.ps1`

## Que incluye

- Impresoras fiscales: PNP, Rigaza, TheFactory (serial, USB, red, DLL)
- Impresoras ESC/POS: Tickets, comandas cocina, codigos de barra
- Balanzas: Lectura por puerto COM
- Modo emulador: Para desarrollo sin hardware

## Requisitos

- Windows 10/11 o Windows Server 2019+
- Puerto 5059 disponible

---

> Codigo fuente privado — [Zentto ERP](https://zentto.net)
