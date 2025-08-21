# INSTALAÇÃO LOCAL

## Parte 1: Exportar projeto

- [Baixar e extrair o ZIP do projeto no Overleaf](https://www.overleaf.com/learn/how-to/Exporting_your_work_from_Overleaf#Downloading_your_current_project_as_a_.zip_file)

## Parte 2: Baixando pacotes TeX Live

### ![Ubuntu Linux](https://skillicons.dev/icons?i=ubuntu "Ubuntu Linux") Ubuntu Linux

- No terminal, baixar pacotes do TeX Live

      sudo apt update
      sudo apt install -y texlive-latex-recommended texlive-latex-extra texlive-lang-portuguese texlive-fonts-extra texlive-bibtex-extra biber latexmk

### ![Windows 10/11](https://skillicons.dev/icons?i=windows "Windows 10/11") Windows 10/11

- [Baixar o instalador do TeX Live](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe)
- A instalação completa inclui diversos pacotes, resultando na necessidade de cerca de 10GB de espaço em disco.
- Na tela do "Instalador TeX Live", **desmarcar o item: '*Instalar editor TeXworks*'**

## Parte 3: Configurando VSCode

Editando no VSCode (>= 1.96.0):
- Instalar a extensão [Latex Language Support](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support)
- Instalar a extensão [LaTex Workshop (Autor: James Yu)](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- Após carregar a pasta do projeto, use a barra lateral contendo os comandos presentes na extensão TeX:

![LaTeX Workshop Extension](https://vkuhlmann.com/assets/files/VisualStudioCodeDemo-44dc77498e90e4586d28d7caf1c9547d.png "LaTeX Workshop Extension")



