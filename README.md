# Vugger - The Visual Debugger

![vugger2](https://user-images.githubusercontent.com/89490246/185488870-710cde59-2e33-4ed4-b574-e1af585096f5.png)
**Dead Cells (Steam)**

The realtime GPU debugger and modding tool for DirectX 11.  Using ImGui, ReShade and RenderDoc technologies to allow you to peer into the inner workings of your applications graphics pipeline in a more visual manner then a lot of other tools.

Other grahics API's will be supported in the future.  This is closed source at the moment but I aim to open it up once I get my feet on the ground.


## Installation

Simply copy either the 32bit or 64bit dxgi.dll into the same folder as your DirectX 11 application's executable file.  Which one depends on whether your application's executable file is 32bit or 64bit.

Then simply run your app. Once at the point you want to delve deeper into simply press HOME.  

For the first time only you will need to login using your Vugger Discourse username and password that you can register here: https://vugger.org

Once done you can scroll and zoom by dragging the mouse and its wheel.  

This is a super alpha alpha alpha release so expect bugs and is just a sketch of where I want to get to.

Lots of love MajorPainTheCactus



## Compatibility

DeadCells.exe (partial) (DX11 32bit, Steam)

RetroArch.exe (DX11 32bit + 64bit, https://www.retroarch.com)

MultiThreadedRendering11.exe (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 
NBodyGravityCS11.exe (doesn't render main scene properly) (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 
AdaptiveTessellationCS40.exe (dispatches need proper support) (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 
BasicHLSL11.exe (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 
BasicHLSLFX11.exe (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 
CascadedShadowMaps11.exe (resources broken) (DX11 32bit + 64bit, https://github.com/microsoft/DirectX-Graphics-Samples) 


## Screenshots

**MultiThreadedRendering11.exe**

![vugger](https://user-images.githubusercontent.com/89490246/185242089-146e69d6-f467-4d56-b5c1-2698302320d1.png)

**FluidCS11.exe**

![vugger3](https://user-images.githubusercontent.com/89490246/190256614-7de7216d-f66c-4b36-a0e6-48d4745281ac.png)

Zoomed in view of dispatch:

![vugger4](https://user-images.githubusercontent.com/89490246/190761458-ea299a65-ed01-48b7-94c2-207f20f79f7e.png)

