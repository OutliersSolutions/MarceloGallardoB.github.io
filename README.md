---

# Instrucciones de Instalación en Windows

## Opción 1: Usando RubyInstaller

### 1. Descargar RubyInstaller
- Visita [RubyInstaller para Windows](https://rubyinstaller.org/) y descarga la versión recomendada (generalmente la versión **Ruby+Devkit**).

### 2. Ejecutar el Instalador
- Ejecuta el instalador descargado.
- Acepta el acuerdo de licencia.
- Selecciona la carpeta de instalación (la ubicación por defecto suele funcionar bien).
- **Importante:** Marca la opción **"Add Ruby executables to your PATH"** para que puedas usar Ruby desde la línea de comandos.
- Durante la instalación, se te preguntará si deseas instalar el Devkit. Acepta e instala el Devkit siguiendo las instrucciones.

### 3. Verificar la Instalación
Abre una terminal (CMD o PowerShell) y ejecuta:

```bash
ruby -v
```

Deberías ver la versión instalada de Ruby.

---

## Pasos Adicionales

1. **Instalar Dependencias de Ruby:**

   Ejecuta en la raíz de tu proyecto:

   ```bash
   bundle install
   ```

2. **Instalar Dependencias de Node.js:**

   Ejecuta:

   ```bash
   npm install
   ```

3. **Ejecutar el Servidor de Jekyll:**

   Ejecuta:

   ```bash
   bundle exec jekyll serve --config _config.yml,_config.dev.yml
   ```

   Esto ejecutará el servidor y se mostrará la URL para visualizar tu sitio en el navegador.

---
