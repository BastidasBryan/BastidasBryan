from pathlib import Path

readme = """<div align="center">

# Bryan Bastidas Baque

**Estudiante técnico en informática**

Desarrollo de software · Redes · IoT · Visualización 3D

<br>

<a href="https://github.com/BastidasBryan">
  <img src="https://img.shields.io/badge/GitHub-BastidasBryan-24292e?style=flat-square&logo=github&logoColor=white" alt="GitHub">
</a>
<a href="https://www.linkedin.com/in/bryan-bastidas-baque-a48773443/">
  <img src="https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

</div>

---

## Perfil

Soy estudiante técnico en informática con intereses que abarcan el desarrollo de software, las redes, los microcontroladores y el diseño 3D. Me gusta aprender cómo se relacionan estas áreas y aplicarlas en proyectos prácticos.

Actualmente me interesan especialmente **JavaScript, Node.js, SQL, TCP/IP, IoT, Blender y Three.js**.

## Tecnologías

<div align="center">

**Desarrollo web**
<br>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">

<br><br>

**Sistemas, datos e IoT**
<br>
<img src="https://img.shields.io/badge/Redes-TCP%2FIP-2563EB?style=flat-square" alt="Redes TCP/IP">
<img src="https://img.shields.io/badge/IoT-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="IoT ESP32">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB">

<br><br>

**Diseño y 3D**
<br>
<img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js">
<img src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white" alt="Blender">

</div>

## Objetivos actuales

| Objetivo | Enfoque |
| --- | --- |
| Domotizar mi habitación | Automatización e integración de dispositivos |
| Ingeniería en Mecatrónica | Continuar mi formación técnica y profesional |
| Ampliar mis conocimientos | Desarrollo, redes, IoT y herramientas 3D |

## Contacto

- **GitHub:** [BastidasBryan](https://github.com/BastidasBryan)
- **LinkedIn:** [Bryan Bastidas Baque](https://www.linkedin.com/in/bryan-bastidas-baque-a48773443/)

---

<div align="center">

*Software, hardware y creatividad en un mismo lugar.*

</div>
"""

path = Path("/mnt/data/README_Bryan_Bastidas_Baque.md")
path.write_text(readme, encoding="utf-8")
print(f"README reorganizado: {path}")
