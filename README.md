Perfecto, aquí tienes un `README.md` completo que incluye:

1. **Descripción del proyecto**
2. **Pasos para abrir y correr el proyecto desde un `.zip`**
3. **Instalación de dependencias y ejecución del backend y frontend**

---

````markdown
# Simulador de Ahorro e Inversión

## Descripción

Esta aplicación web permite simular la evolución financiera personal a lo largo del tiempo, integrando automatizaciones de ahorro y proyecciones de inversión. A través de una interfaz amigable, el usuario puede ingresar sus gastos diarios, definir reglas de redondeo, establecer aportaciones fijas y extraordinarias, así como planificar inversiones a largo plazo considerando el interés compuesto.

El sistema se compone de:

- **Un backend en FastAPI**, que procesa los datos y aplica las reglas financieras definidas.
- **Un frontend en React**, que presenta formularios interactivos y gráficas dinámicas con los resultados.
- **Integración opcional con Docker**, para desplegar fácilmente tanto el servidor como la interfaz.

Está diseñado para ayudar a las personas a entender el impacto de sus hábitos de consumo, ahorro e inversión en su patrimonio futuro.

---

## Cómo abrir y correr el proyecto desde un archivo ZIP

### 1. Extraer el archivo ZIP

- Da clic derecho sobre el archivo `.zip` descargado.
- Selecciona **"Extraer todo"** o usa una herramienta como WinRAR o 7-Zip.
- Asegúrate de mantener la estructura de carpetas:  
  `backend/` para el servidor, y `frontend/` para la interfaz.

### 2. Abrir en Visual Studio Code (VS Code)

- Abre **Visual Studio Code**.
- Selecciona **"Archivo" → "Abrir carpeta"**.
- Elige la carpeta extraída del ZIP (la que contiene `backend/` y `frontend/`).

---

## Requisitos previos

Asegúrate de tener instalado:

- Python 3.10 o superior
- Node.js 18 o superior
- npm (incluido con Node.js)
- (Opcional) Docker

---

## Instalación y ejecución

### Backend (FastAPI)

1. Abrir terminal en la carpeta `backend`:
   ```bash
   cd backend
````

2. Crear un entorno virtual:

   ```bash
   python -m venv venv
   ```

3. Activarlo:

   * En **Windows**:

     ```bash
     .\venv\Scripts\activate
     ```
   * En **Mac/Linux**:

     ```bash
     source venv/bin/activate
     ```

4. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```

5. Ejecutar el servidor:

   ```bash
   uvicorn main:app --reload
   ```

   El servidor estará disponible en:
   [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

### Frontend (React)

1. Abrir nueva terminal y navegar a la carpeta `frontend`:

   ```bash
   cd frontend
   ```

2. Instalar dependencias:

   ```bash
   npm install
   ```

3. Ejecutar el servidor de desarrollo:

   ```bash
   npm start
   ```

   La interfaz estará disponible en:
   [http://localhost:3000](http://localhost:3000)

---

## Uso

1. Introduce tus gastos, rango de fechas, ingresos anuales y años a invertir.
2. Observa el desglose del ahorro acumulado, la inversión proyectada y el monto ajustado por inflación.
3. Visualiza gráficas comparativas de crecimiento a lo largo de los años.

---

## Autoría

**Desarrolladora JR:** Veraza García Amy Valentina

