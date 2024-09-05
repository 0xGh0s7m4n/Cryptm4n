Codigo escrito en Python que permite cifrar y descifrar archivos utilizando el algoritmo AES (Advanced Encryption Standard). Está desarrollado con la biblioteca tkinter para crear una interfaz gráfica de usuario (GUI) y cryptography para realizar las operaciones de cifrado y descifrado.

**Funcionalidades principales:** 

Cifrado de archivos:
- El usuario selecciona un archivo y proporciona una contraseña
- El archivo es cifrado utilizando la contraseña, un algoritmo de derivación de claves (PBKDF2HMAC), y AES en modo CBC
- El archivo original es eliminado y se genera un nuevo archivo con extensión .encrypted

Descifrado de archivos:
- El usuario selecciona un archivo previamente cifrado (con extensión .encrypted) y proporciona la contraseña.
- El archivo es descifrado y restaurado a su formato original.

**Usos:**
Protección de archivos: La aplicación es útil para asegurar archivos personales o sensibles. Cualquier archivo puede ser cifrado y permanecer inaccesible a menos que se disponga de la contraseña correcta.
Intercambio seguro de archivos: El cifrado permite compartir archivos de manera segura, ya que solo el destinatario con la contraseña correcta podrá descifrarlos.

**Descargar e instalar:**

    git clone https://github.com/0xGh0s7m4n/Cryptm4n.git
    cd Cryptm4n
    chmod +x cryptm4n
    pip3 install -r requirements.txt
    ./cryptm4n

![image](https://github.com/user-attachments/assets/07abf7c1-15d9-4be1-af52-499596e66acd)

![image](https://github.com/user-attachments/assets/f9feb4d6-67ca-493d-b927-d3a9e9a5e7cf)

![image](https://github.com/user-attachments/assets/34b49b42-2a39-4750-9a15-799b8fcb687e)

![image](https://github.com/user-attachments/assets/f393a7ec-7f97-4b01-824b-e62f00484fb8)

![image](https://github.com/user-attachments/assets/9e7c6706-d820-4b1d-9455-8e10eb7f093d)

**Ejemplos:**

Encriptar Archivo

![image](https://github.com/user-attachments/assets/2d297931-8d8f-4e97-bb85-88b9f2cf42f8)

Crear contraseña

![image](https://github.com/user-attachments/assets/3e61f10e-a18b-4cca-986b-60e960b8eb61)

Archivo encriptado exitosamente

![image](https://github.com/user-attachments/assets/732d74e3-0234-42d0-80b4-eb09fb5b0b6a)

Desencriptar Archivo

![image](https://github.com/user-attachments/assets/33cc6883-6f5e-444b-a376-9b1b209d86af)

![image](https://github.com/user-attachments/assets/202045b1-6336-4099-a7db-0f173460ac2a)

Archivo desencriptado exitosamente

![image](https://github.com/user-attachments/assets/91107b66-53f0-4195-8c73-5214cc6d5db8)












