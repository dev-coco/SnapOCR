# SnapOCR

A lightweight and minimalist screenshot text recognition tool designed specifically for macOS.

## Features

- **Minimal Interaction**: No complex windows. Quickly triggered via global keyboard shortcuts.  
- **Native Engine**: Built on macOS Vision framework for high-accuracy offline text recognition.  
- **Smart Feedback**: Once recognition is complete, the text is automatically copied to the clipboard, accompanied by a subtle semi-transparent HUD notification.  
- **Fully Private**: All processing is performed locally without any network connection, ensuring data security.  
- **Smart Settings**: Supports launch at startup and flexible layout control.  

## How to Use

- **Start Capture**: Press the default shortcut `⇧⌘2` (Shift + Command + 2).  
- **Automatic Processing**: After selecting an area, the text is instantly recognized and copied to the clipboard.  
- **Open Settings**: Click the menu bar icon and select “Settings” to adjust language and preferences.  

## Configuration Options

You can customize the app in the settings panel:

| Option | Description |
| :--- | :--- |
| **Recognition Language** | Switch between different languages for OCR recognition |
| **Preserve Line Breaks** | Keep original paragraph structure or merge into a single line |
| **Launch at Login** | Automatically start the tool when the system boots |
| **Hotkey** | Customize the shortcut that best fits your workflow |

## Getting Started

### Requirements
- macOS 13.0+  
- Xcode 14.6+ (for building the project)  