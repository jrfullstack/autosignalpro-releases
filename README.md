# AutoSignalPro — descargas / downloads

[Español](#español) · [English](#english)

---

## Español

Aquí se publican el instalador de la **app de escritorio de AutoSignalPro** para Windows y el **EA** para MetaTrader 5. No hay código: solo las versiones.

### Qué descargar

En la **[última versión](https://github.com/jrfullstack/autosignalpro-releases/releases/latest)**, en el apartado «Assets»:

| Archivo | Para qué |
|---|---|
| `AutoSignalPro-Setup-X.Y.Z.exe` | **La app.** Es lo único que necesitas: al instalarse, pone el EA y sus librerías en todos tus MetaTrader 5. |
| `AutoSignalPro-EA-X.YY.zip` | El EA y sus librerías sueltos, solo para instalarlo a mano en un PC donde no esté la app. |

Los demás archivos (`latest.yml`, `.blockmap`) los usa la app para actualizarse sola; no hace falta bajarlos.

### Instalar la app

1. Descarga y ejecuta **`AutoSignalPro-Setup-X.Y.Z.exe`**.
2. **Si Windows muestra «Windows protegió su PC»** (SmartScreen): el instalador todavía no está firmado digitalmente. Pulsa **«Más información» → «Ejecutar de todos modos»**.
3. Abre la app e **inicia sesión con tu cuenta de [autosignalpro.com](https://www.autosignalpro.com)**.
4. La app instala sola el EA y sus librerías en tus MetaTrader 5. Puedes verlo en **Ajustes → «MetaTrader y EA»**.

### Preparar MetaTrader 5

1. En MetaTrader: **Herramientas → Opciones → Asesores expertos → marca «Permitir importar DLL»** (el EA la necesita para hablar con la app). También puedes marcarla al poner el EA en un gráfico, en la pestaña «Común».
2. Pon el EA **«Auto Signal Pro»** (en el Navegador, carpeta Asesores expertos → Auto Signal Pro) en un gráfico de la cuenta.
3. En la app, **Cuentas** debería mostrar la cuenta con «EA conectado».

### Actualizaciones

- **La app se actualiza sola** cuando sale una versión nueva.
- **El EA no se cambia solo** mientras MetaTrader está abierto (MetaTrader no carga un EA nuevo con el gráfico abierto). Cuando una versión trae EA nuevo, la app avisa con **«Se detectó una nueva versión del EA»**: pulsa **«Actualizar EA»** y la app cerrará ese MetaTrader, instalará el EA y lo volverá a abrir. Las notas de cada versión dicen si hay que hacerlo.

### Instalar el EA a mano (otro PC, sin la app)

1. Descarga **`AutoSignalPro-EA-X.YY.zip`** y descomprímelo.
2. **Cierra MetaTrader** y ejecuta **`Instalar-EA.cmd`**: copia el EA y las librerías en todos los MetaTrader 5 de ese PC.
3. Sigue los pasos de «Preparar MetaTrader 5».

### Requisitos

Windows 10 u 11 de 64 bits, MetaTrader 5 y una cuenta en [autosignalpro.com](https://www.autosignalpro.com).

---

## English

This is where the **AutoSignalPro desktop app** installer for Windows and the **EA** for MetaTrader 5 are published. There is no code here: only the releases.

### What to download

In the **[latest release](https://github.com/jrfullstack/autosignalpro-releases/releases/latest)**, under "Assets":

| File | What for |
|---|---|
| `AutoSignalPro-Setup-X.Y.Z.exe` | **The app.** It's all you need: once installed, it puts the EA and its libraries into all your MetaTrader 5 terminals. |
| `AutoSignalPro-EA-X.YY.zip` | The EA and its libraries on their own, only to install it by hand on a PC without the app. |

The other files (`latest.yml`, `.blockmap`) are used by the app to update itself; you don't need them.

### Install the app

1. Download and run **`AutoSignalPro-Setup-X.Y.Z.exe`**.
2. **If Windows shows "Windows protected your PC"** (SmartScreen): the installer isn't digitally signed yet. Click **"More info" → "Run anyway"**.
3. Open the app and **sign in with your [autosignalpro.com](https://www.autosignalpro.com) account**.
4. The app installs the EA and its libraries into your MetaTrader 5 terminals on its own. You can check it in **Settings → "MetaTrader and EA"**.

### Prepare MetaTrader 5

1. In MetaTrader: **Tools → Options → Expert Advisors → tick "Allow DLL imports"** (the EA needs it to talk to the app). You can also tick it when attaching the EA to a chart, on the "Common" tab.
2. Attach the **"Auto Signal Pro"** EA (in the Navigator, Expert Advisors → Auto Signal Pro) to a chart of the account.
3. In the app, **Accounts** should show the account with "EA connected".

### Updates

- **The app updates itself** when a new version is out.
- **The EA isn't replaced on its own** while MetaTrader is open (MetaTrader doesn't load a new EA with the chart open). When a release ships a new EA, the app shows **"A new EA version was detected"**: press **"Update EA"** and the app will close that MetaTrader, install the EA and open it again. Each release's notes say whether you need to.

### Install the EA by hand (another PC, without the app)

1. Download **`AutoSignalPro-EA-X.YY.zip`** and unzip it.
2. **Close MetaTrader** and run **`Instalar-EA.cmd`**: it copies the EA and its libraries into every MetaTrader 5 on that PC.
3. Follow "Prepare MetaTrader 5".

### Requirements

64-bit Windows 10 or 11, MetaTrader 5 and an [autosignalpro.com](https://www.autosignalpro.com) account.
