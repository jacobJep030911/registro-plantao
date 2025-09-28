# 🏥 Registro de Plantão

Aplicativo Android desenvolvido para auxiliar profissionais em ambientes de cuidado na organização de informações durante o plantão. Criado com apoio de inteligência artificial, o app oferece uma interface intuitiva para registrar dados clínicos, tarefas realizadas, observações e relatórios finais.

---

## 🌐 Idiomas Disponíveis / Available Languages / Idiomas Disponibles

- 🇧🇷 Português do Brasil
- 🇬🇧 English
- 🇪🇸 Español

---

## 🇧🇷 Funcionalidades

- Tela Inicial e Dados Gerais
- 📋 Cardápio e Observações do Jantar
- 💊 Medicação e Cuidados Específicos
- 🌙 Rotina Noturna, Relatórios e Tarefas
- 📘 Relatório Master Editável
- 💉 Pressão Arterial e Cateterismo

📦 [Baixar APK de teste](app-debug.apk)  
🔗 [Ver repositório no GitHub](https://github.com/thiagoplacido/registro-plantao)

---

## 🇬🇧 Features

- Home Screen and General Data
- 📋 Dinner Menu and Observations
- 💊 Medication and Specific Care
- 🌙 Night Routine, Reports and Tasks
- 📘 Editable Master Report
- 💉 Blood Pressure and Catheterization

📦 [Download test APK](app-debug.apk)  
🔗 [View GitHub repository](https://github.com/thiagoplacido/registro-plantao)

---

## 🇪🇸 Funcionalidades

- Pantalla inicial y datos generales
- 📋 Menú de cena y observaciones
- 💊 Medicación y cuidados específicos
- 🌙 Rutina nocturna, informes y tareas
- 📘 Informe Master editable
- 💉 Presión arterial y cateterismo

📦 [Descargar APK de prueba](app-debug.apk)  
🔗 [Ver repositorio en GitHub](https://github.com/thiagoplacido/registro-plantao)

---

## 📸 Galeria Interativa

<style>
  .gallery img {
    width: 180px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    cursor: pointer;
    transition: transform 0.2s;
  }
  .gallery img:hover {
    transform: scale(1.05);
  }
  .lightbox {
    display: none;
    position: fixed;
    z-index: 999;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.8);
    justify-content: center;
    align-items: center;
  }
  .lightbox img {
    max-width: 90%;
    max-height: 80%;
    border-radius: 10px;
  }
  .close-btn {
    position: absolute;
    top: 20px; right: 30px;
    font-size: 30px;
    color: white;
    cursor: pointer;
  }
</style>

<div class="gallery" style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
  <img src="screenshots/1.png" onclick="document.getElementById('light1').style.display='flex'" alt="Tela 1">
  <img src="screenshots/2.png" onclick="document.getElementById('light2').style.display='flex'" alt="Tela 2">
  <img src="screenshots/3.png" onclick="document.getElementById('light3').style.display='flex'" alt="Tela 3">
  <img src="screenshots/4.png" onclick="document.getElementById('light4').style.display='flex'" alt="Tela 4">
  <img src="screenshots/5.png" onclick="document.getElementById('light5').style.display='flex'" alt="Tela 5">
  <img src="screenshots/6.png" onclick="document.getElementById('light6').style.display='flex'" alt="Tela 6">
</div>

<!-- Lightboxes -->
<div id="light1" class="lightbox" onclick="this.style.display='none'">
  <span class="close-btn" onclick="document.getElementById('light1').style.display='none'">&times;</span>
  <img src="screenshots/1.png">
</div>
<div id="light2" class="lightbox" onclick="this.style.display='none'"><span class="close-btn" onclick="document.getElementById('light2').style.display='none'">&times;</span><img src="screenshots/2.png"></div>
<div id="light3" class="lightbox" onclick="this.style.display='none'"><span class="close-btn" onclick="document.getElementById('light3').style.display='none'">&times;</span><img src="screenshots/3.png"></div>
<div id="light4" class="lightbox" onclick="this.style.display='none'"><span class="close-btn" onclick="document.getElementById('light4').style.display='none'">&times;</span><img src="screenshots/4.png"></div>
<div id="light5" class="lightbox" onclick="this.style.display='none'"><span class="close-btn" onclick="document.getElementById('light5').style.display='none'">&times;</span><img src="screenshots/5.png"></div>
<div id="light6" class="lightbox" onclick="this.style.display='none'"><span class="close-btn" onclick="document.getElementById('light6').style.display='none'">&times;</span><img src="screenshots/6.png"></div>

---

## 📦 Build

- Versão / Version / Versión: `0.1`  
- Última Atualização / Last Update / Última Actualización: `2023-07-10`  
- Ambiente / Environment / Entorno: `Produção / Production`

---

## ✍️ Autor / Author / Autor

**Thiago Placido**  
Desenvolvedor iniciante com perfil investigativo e realista. Apaixonado por soluções práticas, interfaces funcionais e tecnologia com propósito.

---

## 📄 Licença / License / Licencia

Este projeto está sob a licença MIT.  
This project is under the MIT License.  
Este proyecto está bajo la licencia MIT.
