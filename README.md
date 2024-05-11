
Custom tmux Configuration

## Installation
```bash
git clone https://github.com/shawonsec/tmux.git
cd tmux
mv tmux.conf   ~/.tmux.conf
```
## Features 
Prefix Key Configuration

    Set Prefix Key: The default prefix key (Ctrl+b) has been changed to Ctrl+j for easier access.
    Unset Default Prefix Key: The default prefix key (Ctrl+b) has been unset (unbind-key C-b).

Pane Management

    Vertical and Horizontal Split: Key bindings have been set for easier vertical (v) and horizontal (h) pane splitting.

    Alt-Arrow Key Navigation: Use Alt+Arrow keys to switch between panes without using the prefix key.

    Shift-Arrow to Switch Windows: Shift+Arrow keys are configured to switch between windows.

    Reorder Windows: Easily reorder windows using Ctrl+Shift+Arrow.

Other Functionalities

    Synchronize Panes: Press y to toggle synchronized mode for all panes.

    Reload Configuration: Reload tmux configuration with Ctrl+j + r.
    Clear History: Press Ctrl+j + L to clear the pane history.

    Copy-Paste Functionality: Vi-style key bindings are enabled for copy-pasting with v for selection and y for copying.

    Mouse Mode: Mouse support is enabled (set -g mouse on) for easier navigation.

    Lengthen Display Time: Status messages and panes are displayed for longer durations.
    Base Index Configuration: Base index for windows and panes is set to 1 rather than 0.

    Automatic Window Renaming: Windows are automatically renamed based on the running command.
    No Escape Key Delay: No delay for escape key press is set (set -sg escape-time 0).

    Custom Theme: Custom theme configuration for status bar, windows, and panes.

    Monitor Activity: Background color changes for tabs when activity occurs.

Status Bar Configuration

    Status Bar Alignment: Centered alignment of the status bar.
    
    Status Bar Styling: Custom styling for the status bar with information about hostname, session name, and time.
## Screenshots

![App Screenshot](https://github.com/shawonsec/shawonsec/blob/main/tmux-conf.png)

