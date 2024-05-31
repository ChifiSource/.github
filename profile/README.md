<div align = "center">
<a href="https://github.com/ChifiSource/ChifiSource.jl"><img src = "https://github.com/ChifiSource/image_dump/blob/main/chifi/olivesquarepurp.png" width="110"></a>

<h5><a href="https://github.com/ChifiSource/">chifi</a> | an open-source software dynasty. | <a href="https://chifi.dev">blog</a> </h5>
</div>


###### [skip readme](https://github.com/ChifiSource#thanks)
## map
- [**web**](#web)
  - [**websites**](#websites)
    - [ChifiDocs](#chifi-docs)
  - [**servers**](#servers)
- [**julia packages**](#julia-packages)
  - [**parametric**](#parametric) - Extensible base ecosystem tools.
    - [info](#parametric)
  - [**toolips**](#toolips) - web and server-development framework.
    - [info](https://github.com/ChifiSource#a-manic-web-development-framework)
    - [extensions](#toolips-extensions)
  - [**gattino**](#gattino) - Composable data visualizations for Julia.
    - [info](https://github.com/ChifiSource#elegant-visualizations-for-julia)
    - [extensions](#gattino-extensions)
  - [**olive**](#olive) - Extensible notebook/IDE for julia.
    - [info](https://github.com/ChifiSource#pure-julia-notebooks!)
    - [extensions](https://github.com/ChifiSource#olive-extensions)
      - [cells](#cells)
      - [languages and formats](#languages-and-formats)
      - [project editors](#project-editors)
      - [servers](#servers)
  - [**algebra frames**](#algebra-frames) - Out-of-memory data for Julia.
  - [**tumble**](#tumble) - `AlgebraFrames`-based machine-learning.
  - [**other stuff**](#stuff) - Random packages.
#### web
`Chifi` hosts several `Toolips`-based [websites](#websites), and for this we have also created and [servers](#servers) to deploy these projects.
#### websites
###### chifi docs
<div align="center">
  <a href="https://github.com/ChifiSource/ChifiDocs.jl">
<img src="https://github.com/ChifiSource/image_dump/blob/main/chifi/chifidocs.png" width=160></img>
  </a>
</div>
`ChifiDocs` is a work-in-progress documentation website, this overview will be updated shortly.

#### servers

<div align="center">
  </br>
   </a>
     </br>
  <a href="https://github.com/ChifiSource/ChiNS.jl">
  <img width = 100 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/chins/chifiNS.png">
  </a>
  <a href="https://github.com/ChifiSoure/ChiProxy.jl">
    <img width=150 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/tools/chifiProxy.png">
  </a>
  <a href="https://github.com/ChifiSource/ChiDB.jl">
    <img width=100 height=45 src="https://github.com/ChifiSource/image_dump/blob/main/laboratory/tools/chifiDB.png">
  </a>
</div>

# julia packages
Over the years, we have been working to build a *pretty radical* Julia package ecosystem. This ecosystem is meant to facilitate data-driven fullstack web-development and Data Science (*combined into one*) with julia.
## parametric
<div align="center">
<table>
 <tr>
   <th><a href = "https://github.com/ChifiSource/ParametricProcesses.jl" width = 50><img width = 200 src="https://github.com/ChifiSource/image_dump/blob/main/parametricprocesses/parproc.png"></a></th>
   <th><a href = "https://github.com/ChifiSource/IPy.jl"><img width = 120 src="https://github.com/ChifiSource/image_dump/blob/main/ipyjl/logo.png" ></a></th>
 </tr>
  <tr>
    <td align="center">
      
  [![version](https://juliahub.com/docs/General/ParametricProcesses/stable/version.svg)](https://juliahub.com/ui/Packages/General/ParametricProcesses)
    <td align="center">
    
  [![version](https://juliahub.com/docs/General/IPyCells/stable/version.svg)](https://juliahub.com/ui/Packages/General/IPyCells)
  
  </td>
  </td>
  </tr>
</table>
</div>

The *parametric ecosystem* offers a number of packages and tools for varying tasks which feature parametric data-structures for use with multiple dispatch.

## toolips

<table align="center">
        <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsServables.jl" width = 100><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsservables.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/Toolips.jl" width = 100><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolips03.png"></a></th>
        </tr>
  <tr>
  <td align="center">
    
  [![version](https://juliahub.com/docs/General/ToolipsServables/stable/version.svg)](https://juliahub.com/ui/Packages/General/ToolipsServables)
  
  </td>
    <td align="center">
    
  [![version](https://juliahub.com/docs/General/Toolips/stable/version.svg)](https://juliahub.com/ui/Packages/General/Toolips)
  
  </td>
  </tr>
</table>

#### a manic web-development framework
`Toolips` is a web-development framework centered around extensibility and multiple dispatch. `Toolips` is an *all-in-one* web-development framework capable of programming low-level servers, APIs, and fullstack web applications.

##### toolips extensions

<table align="center">
        <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsSession.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipssession.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsRemote.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsremote.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/ToolipsUDP.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsudp.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsORM.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsORM.png"></a></th>
  </tr>
    <tr><td align="center">
      
  [![version](https://juliahub.com/docs/General/ToolipsSession/stable/version.svg)](https://juliahub.com/ui/Packages/General/ToolipsSession)
    
  </td>
  <td>
    
  </td>
  <td>
    
  </td>
  <td>
    
  </td>
  </tr>
          <tr>
    <th><a href = "https://github.com/ChifiSource/ToolipsManager.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsmanager.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsUploader.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsuploader.png"></a></th>
          <th><a href = "https://github.com/ChifiSource/ToolipsCrawl.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipscrawl.png"></a></th>
    <th><a href = "https://github.com/ChifiSource/ToolipsSVG.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/toolips/toolipsSVG.png"></a></th>
  </tr>
  <tr><td>
    
  </td>
  <td>
    
  </td>
  <td>
    
  </td>
  <td align="center">

  [![version](https://juliahub.com/docs/General/ToolipsSVG/stable/version.svg)](https://juliahub.com/ui/Packages/General/ToolipsSVG)
    
  </td>
  </tr>
  
</table>

<table align="center">
<tr>
<th><a href = "https://github.com/ChifiSource/Vulta.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/raw/main/toolips/vulta/vultaatte.png"></a></th>
</tr>
<tr>
<td align = "center">
      
**unreleased**


</td>
</tr>
</table>

## gattino

<div align = "center">
<th><a href = "https://github.com/ChifiSource/Gattino.jl" width = 50><img width = 125 src="https://github.com/ChifiSource/image_dump/blob/main/gattino/gattino.png"></a></th>
    
[![version](https://juliahub.com/docs/General/Gattino/stable/version.svg)](https://juliahub.com/ui/Packages/General/Gattino)
    
</div>

###### elegant visualizations for julia
Gattino is Toolips-based, extensible plotting for Julia. Featuring ...
- an extension **ecosystem**
- **modular** plot components
- **hyper-composability**
- toolips **components**
- and powerful **layout** syntax.

`Gattino` provides these capabilities by wrapping an `svg` window, a `Component{:svg}` from [ToolipsServables](https://github.com/ChifiSource/ToolipsServables.jl), into a proprietary type to be used with an API that scales to the dimensions of that type -- the `Context`.

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

## olive
<div align="center" style = "box-pack: start;">
  </br>
  <a href = https://github.com/ChifiSource/Olive.jl>
  <img width = 250 src="https://github.com/ChifiSource/image_dump/blob/main/olive/olivemain.png">
  <br>
  
[![version](https://juliahub.com/docs/General/Olive/stable/version.svg)](https://juliahub.com/ui/Packages/General/Olive)

**(pre-release II)**

</div>

###### pure julia notebooks!
Welcome to olive! Olive is a **pure julia** notebook editor built on the back of multiple dispatch. Through multiple dispatch, olive is able to change functionality entirely by simply having new methods. Using extensions, olive can edit **any** file. Among other things, olive features ...
- regular **julia modules**
- *parametric* **extension** loading
- **tabbing** notebooks
- **customizable** *everything*
- reading of pluto, julia, olive, **and** ipython notebooks
- a full **file-browser**
- **deployability**
- and a **two-pane** design.
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

## algebra frames

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
</table>




    
  </br>
  </br>
    </br>
    
  </div>

## thanks
