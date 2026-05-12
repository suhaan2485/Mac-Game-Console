# Mac-Game-Console
This is a simple project where in i would test games and windows files which are either not supported in mac or does not work perfectly, using softwares like crossover

Run Windows games and .exe apps on Apple Silicon Macs using tools like CrossOver.

Mac Console is a personal testing project focused on running Windows-only games, launchers, and applications on macOS ARM architecture.

## About The Project

Many games and Windows applications are unsupported on macOS, especially on Apple Silicon devices. This project documents methods, fixes, and tests used to run those applications using translation and compatibility layers such as:

- CrossOver
- Wine
- Whisky
- Game Porting Toolkit (GPTK)
- Rosetta 2


## Features

- Run .exe files 
- Test unsupported Windows games
- Launcher compatibility experiments
- Apple Silicon focused
- Performance and stability tracking
- CrossOver configuration testing

## Supported Platforms

- macOS Ventura
- macOS Sonoma
- Apple Silicon Macs
  - M1
  - M2
  - M3

Intel Macs may work, but this project mainly targets ARM-based Macs (M2+ wrok better) .

## Software Used

Software = Purpose 

 CrossOver = Running Windows applications 
 Wine  = Windows compatibility layer 
 Whisky = Wine frontend for macOS 
 GPTK = Apple's Game Porting Toolkit 
 Rosetta 2 = x86 translation on Apple Silicon 

## Example Tests

Some examples of what may be tested here:

- Windows game launchers
- Steam Windows games
- Epic Games Launcher
- Unreal Engine games
- DRM compatibility
- Controller support
  
Some games may run surprisingly well, while others may have:
- Stuttering
- Missing textures
- Audio issues
- Launcher crashes
- FPS instability

(The conversion is not really expected smooth it can vary with app configurations and uses)

##  Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Mac-Game-Console.git
