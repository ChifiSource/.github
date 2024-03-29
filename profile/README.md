<div align = "center">
<a href="https://github.com/ChifiSource/ChifiSource.jl"><img src = "https://github.com/ChifiSource/image_dump/blob/main/chifi2024.png" width="250"></a>

**unreleased**

<h5><a href="https://github.com/ChifiSource/">chifi</a> | an open-source software dynasty. | <a href="https://chifi.dev">blog</a> </h5>
</div>


###### [skip readme](https://github.com/ChifiSource#thanks)
## map
- [**web**](#web)
  - [**websites**](#websites)
    - [laboratory](#laboratory)
    - [servers](#servers)
- [**julia packages**](#julia-packages)
  - [**parametric processes**](#parametric-processes)
    - [info](#parametric-processes)
  - [**toolips**](#toolips) - Extensible web-development.
    - [info](https://github.com/ChifiSource#a-manic-web-development-framework)
    - [toolips 0.3](https://github.com/ChifiSource#toolips-0.3)
    - [toolips 0.2](https://github.com/ChifiSource#toolips-0.2)
  - [**olive**](#olive) - Extensible notebook/IDE for julia.
    - [info](https://github.com/ChifiSource#pure-julia-notebooks!)
    - [extensions](https://github.com/ChifiSource#olive-extensions)
      - [cells](#cells)
      - [languages and formats](#languages-and-formats)
      - [project editors](#project-editors)
      - [servers](#servers)
  - [**gattino**](#gattino) - Dashboards and plots for Julia.
    - [info](https://github.com/ChifiSource#elegant-visualizations-for-julia)
    - [extensions](#gattino-extensions)
  - [**algia**](#algia)
  - [**tumble**](#tumble)
  - [**other stuff**](#stuff) - Random ecosystem packages.
#### web

#### websites
###### laboratory
Laboratory is an all-in-one place to manage repositories, projects, their development and their deployment. This is the precursor to `OliveCreator`, which is going to use `Laboratory` for project and file management for clients. In essence, the goal is to have a one-stop-shop to develop, maintain, work with and even deploy projects.

<div align="center">
  </br>
   </a>
     </br>
    <a href = "https://github.com/ChifiSource/ChifiLaboratory.jl">
  <img width = 350 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/chifilab.png">
  </a>
</div>
    

    
**unreleased** [source](https://github.com/ChifiSource/OliveCreator.jl)
</div>

<table>
  <tr><th>
    <a href = https://github.com/ChifiSource/OliveCreator.jl>
  <img width = 100 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivecreator.png">
  </a>
    </th>
    <th>
    <a href = https://github.com/ChifiSource/ChifiDocumentation.jl>
  <img width = 100 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/modules/documentation.png?raw=true">
  </a>
    </th>
  </tr>
</table>
</div>

###### servers
There are several different steps to web-infastructure, from the TLD server that sends a packet to your DHCP server all the way to the `Toolips` `WebServer` and accompanying Proxy servers. Some of these have already been created for `chifi` projects, so here they are.

<div align="center">
  </br>
   </a>
     </br>
  <img width = 100 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/chins/chifiNS.png">
    <img width=150 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/tools/chifiProxy.png">
    <img width=100 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/tools/chifiDB.png">
</div>

# julia packages
Over the years, we have been working to build a *pretty radical* Julia package ecosystem. This ecosystem is meant to facilitate data-driven fullstack web-development and Data Science (*combined into one*) with julia.
##### parametric processes
`ParametricProcesses` offers high-level `Worker` management for Julia for parallel computing. This package is primarily intended to be used with multi-threading, but the workers that manage the processes are parametric and their functionality can be changed to fit many different contexts. The main objective of this project is to facilitate multi-threaded process management for the `Toolips` web-development framework.

<div align="center">
<table>
 <tr>
   <th><a href = "https://github.com/ChifiSource/ParametricProcesses.jl" width = 50><img width = 200 src="https://github.com/ChifiSource/image_dump/blob/main/parametricprocesses/parproc.png"></a></th>
 </tr>
  <tr>
    <td align="center">
      
  [![version](https://juliahub.com/docs/General/ParametricProcesses/stable/version.svg)](https://juliahub.com/ui/Packages/General/ParametricProcesses)
  
  </td>
  </tr>
</table>
</div>

## toolips

<div align="center" style = "box-pack: start;">
  </br>
  <a href = https://github.com/ChifiSource/Toolips.jl></a>
  <img width = 200 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolips.svg"></img>
  </div>
<div align = "left">

#### a manic web-development framework
The toolips ecosystem is all about bringing ease of use and declarative Julia syntax to the world of web-development. The ecosystem revolves around the *Toolips.jl* module, which defines the base types and infastructure for the toolips way of programming. Subsequent packages build on this, and different portions of the ecosystem can be selected incredibly easily and used individually at whim. This makes the framework useful in a much larger variety of applications; from minimalist web-development to enormous one-page apps. Toolips was originally conceived to build *Olive.jl*, and more than provides on the tools to do so.

- `Toolips` is currently undergoing a breaking ecosystem version step from version `0.2` to version `0.3`. This includes the release of a new `Toolips` `0.3` ecosystem, 

###### toolips 0.3 
A new, breaking version of `Toolips` is coming. This *significant* update breaks up the base, removes a lot of reduncancy, adds parallel computing, enhances components and extensbility, reduces overhead, and deprecates `ToolipsServers` in favor of using Julia modules as server structures. With this, there is also a pretty significant rebuild and redistribution of the ecosystem happening... It might take a bit for `0.3` to have all the packages to facilitate `Toolips` `0.2` functionalities. 

<table align="center">
        <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsServables.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsservables.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/Toolips.jl/tree/0.3" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolips03.png"></a></th>
        </tr>
</table>


<table align="center">
        <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsSession.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipssession.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsRemote.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsremote.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/ToolipsUDP.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsudp.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsORM.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsORM.png"></a></th>
  </tr>
  <tr>
    
  </tr>
          <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsManager.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsmanager.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsUploader.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsuploader.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/ToolipsUDP.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipscrawl.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsSVG.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsSVG.png"></a></th>
  </tr>
</table>

###### toolips 0.2.x (current stable)
<div align="center">
  <img width = 200 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolips.svg">
  
  [![version](https://juliahub.com/docs/Toolips/version.svg)](https://juliahub.com/ui/Packages/Toolips/TrAr4)
</div>

##### toolips extensions

<table align="center">
        <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsSession.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipssession.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsDefaults.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsdefaults.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsMarkdown.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsmarkdown.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsBase64.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsbase64.png"></a></th>
  </tr>
  <tr>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsSession/version.svg)](https://juliahub.com/ui/Packages/ToolipsSession/ji8dn)


</td>
    
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsDefaults/version.svg)](https://juliahub.com/ui/Packages/ToolipsDefaults/skvfO)


</td>
    
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsMarkdown/version.svg)](https://juliahub.com/ui/Packages/ToolipsMarkdown/tOv1W)


</td>

<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsBase64/version.svg)](https://juliahub.com/ui/Packages/ToolipsBase64/fFDlQ)


</td>

  </tr>
<tr>
<th><a href = "https://github.com/ChifiSource/ToolipsMemWrite.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsmemwrite.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsExport.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsexport.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsRemote.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsremote.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsUploader.jl" width = 20><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsuploader.png"></a></th>
    </tr>
    <tr>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsMemWrite/version.svg)](https://juliahub.com/ui/Packages/ToolipsMemWrite/4C3HO)


</td>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsExport/version.svg)](https://juliahub.com/ui/Packages/ToolipsExport/16D5e)


</td>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsRemote/version.svg)](https://juliahub.com/ui/Packages/ToolipsRemote/atYct)


</td>
<td align = "center">
      
**unreleased**


</td>
</tr>
<tr>
<th><a href = "https://github.com/ChifiSource/ToolipsManager.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsmanager.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsAuth.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsauth.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsSVG.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsSVG.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsInterpolator.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsinterpolator.png"></a></th>
</tr>
<tr>
<td align = "center">
      
**unreleased**


</td>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsAuth/version.svg)](https://juliahub.com/ui/Packages/ToolipsAuth/9DKkL)


</td>
<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsSVG/version.svg)](https://juliahub.com/ui/Packages/ToolipsSVG/mz5Wt)


</td>

<td align = "center">
      
[![version](https://juliahub.com/docs/ToolipsInterpolator/version.svg)](https://juliahub.com/ui/Packages/ToolipsInterpolator/s1Jlr)


</td>


</tr>
<tr>
<th><a href = "https://github.com/ChifiSource/ToolipsUDP.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsudp.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsORM.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsORM.png"></a></th>
<th><a href = "https://github.com/ChifiSource/ToolipsAV.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsAV.png"></a></th>
</th>
<th><a href = "https://github.com/ChifiSource/ToolipsCrawl.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipscrawl.png"></a></th>
</tr>

</tr>
<tr>
<td align = "center">
      
[![version](https://juliahub.com/docs/General/ToolipsUDP/stable/version.svg)](https://juliahub.com/ui/Packages/General/ToolipsUDP)


</td>
<td align = "center">
      
**unreleased**


</td>
<td align = "center">
      
**unreleased**


</td>
<td align = "center">
      
[![version](https://juliahub.com/docs/General/ToolipsCrawl/stable/version.svg)](https://juliahub.com/ui/Packages/General/ToolipsCrawl)


</td>
</tr>
</table>

## olive
<div align="center" style = "box-pack: start;">
  </br>
  <a href = https://github.com/ChifiSource/Olive.jl>
  <img width = 250 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivemain.png">
  <br>
  
[![version](https://juliahub.com/docs/General/Olive/stable/version.svg)](https://juliahub.com/ui/Packages/General/Olive)

**(pre-release II)**

<table>
  <tr>
  <th><a href = "https://github.com/ChifiSource/IPy.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/ipyjl/logo.png" ></a></th>
  </tr>
  <tr>

  <td align="center">
    
  [![version](https://juliahub.com/docs/General/IPyCells/stable/version.svg)](https://juliahub.com/ui/Packages/General/IPyCells)
  
  </td>
    
  </tr>
</table>
</div>

###### pure julia notebooks!
Welcome to olive! Olive is a **pure julia** notebook editor built on the back of multiple dispatch. Through multiple dispatch, olive is able to change functionality entirely by simply having new methods. Using extensions, olive can edit **any** file. Among other things, olive features ...
- regular **julia modules**
- unparalleled **extensibility**
- **modular** design
- **tabbing** notebooks
- its own **julia** ecosystem
- **customizable** settings
- reading of pluto, julia, olive, **and** ipython notebooks
- exporting to **multiple** formats
- a full **file-browser**
- julia **repl cells**
- module and include cells for **software development**
- **deployability**
- **shared variables** between multiple cell-types
- a **two-pane** design
- **loadable** directories as **profiles**
- **flexible** and modern design
- the ability to edit **any** file
##### olive extensions

<table>
<tr>  
   <th><a href = "https://github.com/ChifiSource/OliveDocBrowser.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivedocbrowser.png" ></a></th>
     <th><a href = "https://github.com/ChifiSource/OliveWorkspaces.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveworkspaces.png" ></a></th>
    <th><a href = "https://github.com/ChifiSource/OliveManager.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivemanager.png" ></a></th>
</tr>
    <tr>
 <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
 <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
    </tr>
</table>

###### cells
<table>
    <tr>
               <th><a href = "https://github.com/ChifiSource/FlexCells.jl"><img width = 80 src="https://github.com/ChifiSource/image_dump/blob/main/olive/flexcells.png" ></a></th>
    <th><a href = "https://github.com/ChifiSource/OliveForms.jl"><img width = 110 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveforms.png"></a></th>
        <th><a href = "https://github.com/ChifiSource/OliveDocBrowser.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveautocomplete.png" ></a></th>
    </tr>
    <tr>
         <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
   <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
    </tr>
</table>

###### languages and formats
<table>
<tr>  
 <th><a href = "https://github.com/ChifiSource/OlivePy.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivepy.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/OliveR.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveR.png"></a></th>
   <th><a href = "https://github.com/ChifiSource/OliveMarkdown.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivemd.png" ></a></th>
   <th><a href = "https://github.com/ChifiSource/OliveImages.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveimages.png" ></a></th>
  </tr>
  
  <tr>

<td align = "center">
      
      
      
[![version](https://juliahub.com/docs/General/OlivePython/stable/version.svg)](https://juliahub.com/ui/Packages/General/OlivePython)
      
      
 </td>
  <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  <td align = "center">
      
      
      
[![version](https://juliahub.com/docs/General/OliveImages/stable/version.svg)](https://juliahub.com/ui/Packages/General/OliveImages)
      
      
 </td>
 </tr>
 <tr>  
 <th><a href = "https://github.com/ChifiSource/OliveClang.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveclang.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/OliveLispSyntax.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivelispsyntax.png"></a></th>
  </tr>
  <tr>
        <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
   <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  </tr>
 </table>
 
###### project editors
<table>
<tr>  
    <th><a href = "https://github.com/ChifiSource/Bouquet.jl"><img width = 110 src="https://github.com/ChifiSource/image_dump/blob/main/olive/bouquet.png"></a></th>
  </tr>
  <tr>
        <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  </tr>
</table>

###### servers


<div align = "left">

<table>
<tr>  
 <th><a href = "https://github.com/ChifiSource/OliveCollaborate.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivecollaborate.png"></a></th>
     <th><a href = "https://github.com/ChifiSource/OlivePermissions.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivepermissions.png"></a></th>
       <th><a href = "https://github.com/ChifiSource/OliveUsers.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/olive/oliveusers.png" ></a></th>
  </tr>
  <tr>

<td align = "center">
      
      
      
**unreleased**
      
      
 </td>
 <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
  <td align = "center">
      
      
      
**unreleased**
      
      
 </td>
</tr>
</table>
      

## gattino

<div align = "center">
<th><a href = "https://github.com/ChifiSource/Gattino.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattino.png"></a></th>
    
**unreleased**
    
</div>

###### elegant visualizations for julia
Gattino is Toolips-based, extensible plotting for Julia. This project's base package is still in early development, but gattino plans to feature
- an extension **ecosystem**
- **modular** plot components
- introspectable plots
- **animated** visualizations.
- toolips **components**
- powerful **layout** syntax

###### gattino extensions

<table>
<tr>  
     <th><a href = "https://github.com/ChifiSource/GattinoInteractive.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattinointeractive.png"></a></th>
 <th><a href = "https://github.com/ChifiSource/Gattino3D.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattino3D.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/GattinoPleths.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattinopleths.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/GattinoPleths.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattinostats.png"></a></th>
</tr>
    <tr>
                <td align="center">

**unreleased**


</td>   
        <td align="center">

**unreleased**


</td>   
        <td align="center">

**unreleased**


</td>   
        <td align="center">

**unreleased**


</td>   
    </tr>
    <tr>  
     <th><a href = "https://github.com/ChifiSource/GattinoSpace.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattinospace.png"></a></th>
</tr>
<tr>
            <td align="center">

**unreleased**


</td>   
</tr>
</table>

## algia
<div align = "center">
<th><a href = "https://github.com/ChifiSource/Algia.jl" width = 50><img width = 150 src="https://github.com/ChifiSource/image_dump/blob/main/algia/algia.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/AlgebraFrames.jl" width = 50><img width = 150 src="https://github.com/ChifiSource/image_dump/blob/main/algia/algebraframes.png"></a></th>
</div>

## algia extensions

<table>
    <tr>
    <th><a href = "https://github.com/ChifiSource/AlgebraStreams.jl.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/algia/algebrastreams.png" ></a></th>
    </tr>
    <tr>
<td align = "center">

**not released**

</td>
</tr>
</table>


## tumble
<div align="center">
 <a href = "https://github.com/ChifiSource/Tumble.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/tumble/tumblemain.png" ></a></th>
 </div>

 **not released**
## stuff
<table>
    <tr>
    <th><a href = "https://github.com/ChifiSource/ParseNotEval.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/parsenoteval/logo.png" ></a></th>
<th><a href = "https://github.com/ChifiSource/CarouselArrays.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/odddata/carousel.png" ></a></th>
      <th><a href = "https://github.com/ChifiSource/RollingArrays.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/rollingarrays/rollingarrays.png" ></a></th>
    </tr>
    <tr>
        <td align = "center">

        
    
      
[![version](https://juliahub.com/docs/ParseNotEval/version.svg)](https://juliahub.com/ui/Packages/ParseNotEval/r4sWd)
      
 </td>
       <td align = "center">
      
[![version](https://juliahub.com/docs/CarouselArrays/version.svg)](https://juliahub.com/ui/Packages/CarouselArrays/aznIg)
      
 </td>
        <td align = "center">
      
[![version](https://juliahub.com/docs/IPyCells/version.svg)](https://juliahub.com/ui/Packages/IPyCells/RqXbK)
      
 </td>
 </tr>

 <tr>
           <td align = "center">
      
[![version](https://juliahub.com/docs/IPyCells/version.svg)](https://juliahub.com/ui/Packages/IPyCells/RqXbK)
      
 </td>
 </tr>

</table>

<table>
<tr>
<th><a href = "https://github.com/ChifiSource/Vulta.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/raw/main/toolips/vulta/vultaatte.png"></a></th>
</tr>
<tr>
<td align = "center">
      
**unreleased**


</td>
</tr>
</table>


    
  </br>
  </br>
    </br>
    
  </div>

## thanks
