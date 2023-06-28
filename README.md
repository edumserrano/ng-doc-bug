# NgDoc repro repo for bug #71

This is a repro repo for ng-doc/ng-doc#71.

## Steps to reproduce the bug

1) `ng new` to create an app:

![ng-new](docs/images/ng-new.png)

2) `ng add @ng-doc/add` to add NgDoc:

![ng-doc-add](docs/images/ng-doc-add.png)

3) `ng g @ng-doc/builder:page "Installation"` to add a page:
  
![ng-add-page](docs/images/ng-add-page.png)

## More info about my system

### Angular CLI version

`ng version`

> Angular CLI: 16.1.2 </br>
> Node: 16.19.1 </br>
> Package Manager: npm 9.6.7 </br>
> OS: win32 x64 </br>
>
> Angular: 16.1.2 </br>
> ... animations, cli, common, compiler, compiler-cli, core, forms </br>
> ... platform-browser, platform-browser-dynamic, router </br>
>
> Package                         Version
> ---------------------------------------------------------
> @angular-devkit/architect       0.1601.2 </br>
> @angular-devkit/build-angular   16.1.2 </br>
> @angular-devkit/core            16.1.2 </br>
> @angular-devkit/schematics      16.1.2 </br>
> @schematics/angular             16.1.2 </br>
> rxjs                            7.8.1 </br>
> typescript                      5.1.5 </br>

### Powershell version

`pwsh -v`

> PowerShell 7.3.5

### OS build

In powershell run `[System.Environment]::OSVersion`

> Platform: Win32NT </br>
> Version: 10.0.19045.0 </br>
> VersionString: Microsoft Windows NT 10.0.19045.0 </br>

Info from about system page:

> Edition	Windows 10 Enterprise </br>
> Version	22H2 </br>
> Installed on 08/03/2023 </br>
> OS build	19045.3086 </br>
> Experience	Windows Feature Experience Pack 1000.19041.1000.0 </br>
