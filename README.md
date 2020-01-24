<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/icon.png"
    alt="icon"/>
</p>

<h1 align="center">
    Figwrapper
</h1>
    
`Figwrapper` is a script that integrates the [Figma](https://www.figma.com/) design tool (web version) generated by [nativefier](https://github.com/jiahaog/nativefier) into a complete, fully integrated application for Linux. It uses the [Electron](https://github.com/electron/electron) wrapper generated, which is further customized, to behave like a proper Linux app.

<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/screenshot.png"
    alt="screenshot"/>
</p>
<br>
<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/screnshot-2.png"
    alt="screenshot-2"/>
</p>
<p align="center"><i>Figma install through Figwrapper under i3-gaps on Fedora 31</i></p>
<br>
<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/screenshot-3.png"
    alt="screenshot-3"/>
</p>
</p>
<p align="center"><i>Figma install through Figwrapper under GNOME on Fedora 31</i></p>

## Requirement
* Internet connection.

## Install
**Don't** download the Zip file from the repo, **it will not** download the main binary since it's stored through Git LFS, you need to clone the repo through git.

```bash
> git clone https://github.com/cristianovitorino/figwrapper.git
> cd figwrapper
> chmod u+x InstallFigma.sh
> sh ./InstallFigma.sh
```

## Uninstall

```bash
> chmod u+x InstallFigma.sh
> sh ./UninstallFigma.sh
```

## Copyright

Figwrapper © 2020 Cristiano Vitorino, MIT License

<div>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png" /></a><br />The Figwrapper logo is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>
</div>
<br>
The Figma logo is a trademark and property of Figma, Inc. and is not affiliated with nor does Figma, Inc. endorse Cristiano Vitorino.
