
## Configurar identidad del desarrollador

Cuando trabajas con Git, es importante registrar quién hace los cambios. Para ello, debes configurar tu nombre y correo globalmente:

### 🔹 Iniciar configuración global

  **git config --global** — Inicia la configuración global de Git

### 🔹 Configurar nombre de usuario

  **git config --global user.name "Francis"**

### 🔹 Configurar correo electrónico

  **git config --global user.email "francis.huerta@utec.edu.pe"**

Esto asegura que todos los commits tengan tu identidad correctamente asociada.

---

## 7. Ver la configuración guardada

Puedes ver cómo se guarda tu configuración global ejecutando:

  **git config --global -e**

Esto abrirá el archivo de configuración en tu editor, y se verá así:

**[user]**
**name = Francis**
**email = francis.huerta@utec.edu.pe**


