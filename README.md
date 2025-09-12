# INSTALAÇÃO LOCAL

## Parte 1: Exportar projeto

- [Baixar e extrair o ZIP do projeto no Overleaf](https://www.overleaf.com/learn/how-to/Exporting_your_work_from_Overleaf#Downloading_your_current_project_as_a_.zip_file)

## Parte 2: Baixando os pacotes do LaTeX

### !["Ubuntu Linux"](https://skillicons.dev/icons?i=ubuntu "Ubuntu Linux") Ubuntu Linux

No terminal, baixar pacotes do TeX Live

      sudo apt update
      sudo apt install -y texlive-latex-recommended texlive-latex-extra texlive-lang-portuguese texlive-fonts-extra texlive-bibtex-extra biber latexmk

### !["Windows 10/11"](https://skillicons.dev/icons?i=windows "Windows 10/11") Windows 10/11

#### 1. MiKTeX

- [Baixar o instalador do MiKTex para Windows](https://miktex.org/download)
- Executar o instalador e seguir as configurações padrão, que fará a instalação na pasta: `C:\Users\NOME_DO_USUARIO\AppData\Local\Programs\MiKTeX`
- Atenção à tela abaixo onde deverá ser feita a opção por "**Yes**" para que pacotes faltantes sejam instalados automaticamente
  
![Install missing packages](https://www.malinc.se/math/latex/images/dontaskme.png)

- Após a instalação, é provável que a tela a seguir (MiKTeX Console) apareça e é importante atualizar os pacotes clicando na **opção 2 ("Update Now")**

<img src="https://livro.curso-r.com/img/instalacao/miktex_windows/win_miktex9.png" alt="Update packages" width="70%"/>

- Quando finalizar a atualização, pode-se fechar a tela do MiKTeX Console e seguir para etapa de instalação do Perl

#### 2. Perl

- [Use o instalador formato MSI do Perl para Windows](https://strawberryperl.com)
- Execute o instalador e siga com as opções padrão

## Parte 3: Configurando VSCode

Editando no VSCode (>= 1.96.0):

- Instalar a extensão [Latex Language Support](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support)
- Instalar a extensão [LaTex Workshop (Autor: James Yu)](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- Após carregar a pasta do projeto, use a barra lateral contendo os comandos presentes na extensão TeX, principalmente:
  - **Compilar Projeto LaTeX** (*Build LaTeX project*)' e **Visualizar PDF LaTeX** (*View LaTeX PDF*)

<img src="https://vkuhlmann.com/assets/files/VisualStudioCodeDemo-44dc77498e90e4586d28d7caf1c9547d.png" alt="LaTeX Workshop Extension"/>

---

## Outra opção (mais pesada) para Windows

- [Baixar o instalador do TeX Live](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe)
- A instalação completa inclui diversos pacotes, resultando na necessidade de cerca de 10GB de espaço em disco.
- Na tela do "Instalador TeX Live", **desmarcar o item: '*Instalar editor TeXworks*'**
