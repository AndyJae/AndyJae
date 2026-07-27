# Andreas Jaenisch — Broadcast Engineer, Berlin

Founder of [medien-support](https://medien-support.com) (est. 2007).  
30+ years of broadcast and live event production. 800+ productions for clients 
including Audi, BMW, Deutsche Bank, HP, and SAP.

Broadcast engineer, cameraman, and vision mixer — with a focus on the engineering 
and software layer behind live productions.

## Projects

### [smart-reset](https://smart-reset.com)
Open-source PTZ camera reset and control tool for broadcast engineers.  
Browser-based. Supports Panasonic (UE30–UE160, HE40–HR140) and BirdDog (P100–P4K).  
Auto-discovers cameras on the network, resets all colour parameters to factory 
defaults, and provides live NDI monitoring with waveform and vectorscope analysis.  
No cloud. No subscription. Runs locally.  
→ [smart-reset-browser](https://github.com/AndyJae/smart-reset-browser)

### [smart-matching](https://www.smart-colormatch.com)
Automated colour matching SaaS for PTZ cameras in live broadcast environments.  
Measures a live camera feed against a DSC Labs reference chart, computes per-patch 
RGB delta, and drives camera parameters directly via manufacturer API — iteratively, 
until every patch converges within tolerance. No LUTs. No post-processing.  
Currently in active development.  

### [X-Touch PTZ Control](https://github.com/AndyJae/X-Touch_PTZ_Control)
MIDI shading controller for Panasonic PTZ cameras (17 AW-series models), 
built around the Behringer X-Touch Extender and a local web UI.  
Motorized faders drive iris live; per-channel encoders control gain, pedestal 
and ND filter. Bidirectional sync — changes from the camera's own web interface 
update faders, scribble strips and UI in real time. Bitfocus Companion integration.  
Works standalone via web UI, the hardware controller is optional.  

### [Panasonic PTZ Emulator](https://github.com/AndyJae/Panasonic_PTZ_Emulator)
Standalone Panasonic AW/AK-series camera emulator — simulates the CGI protocol 
of 17 camera models including both command dialects, per-model gain/pedestal 
behaviour, error responses, and the update-notification push channel.  
Built for developing and testing smart-reset and X-Touch PTZ Control without 
physical hardware. Includes a control UI for model selection, live state 
monitoring and error injection.

### [claude-code-usage](https://github.com/AndyJae/claude-code-usage)
VSCode extension that shows Claude Code API usage limits (5h/7d) in the status bar.  
Colour-coded indicator. Available on the VSCode Marketplace.
→ [VSC plugin](https://marketplace.visualstudio.com/items?itemName=AndJae.claudecode-usage)

## medien-support

[medien-support](https://medien-support.com) is a Berlin-based technical services 
company for live productions, founded in 2007. Services include video TD, broadcast 
consulting, system design and integration, and custom automation software for 
broadcast workflows.

## Contact

- Web: [medien-support.com](https://medien-support.com)  
- LinkedIn: [andreas-jaenisch-4140036](https://linkedin.com/in/andreas-jaenisch-4140036)
