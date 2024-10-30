Here's a README file for your Neovim config repo:

---

# Neovim Configurations

This repository contains custom configurations for Neovim based on [NvChad](https://github.com/NvChad/NvChad).

## Installation

Follow these steps to set up your Neovim with NvChad and this custom configuration.

### Prerequisites

Make sure you have Neovim installed. [Install Neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim).

### Steps

1. **Remove Existing Configurations**  
   Delete the current Neovim configurations if they exist:
   ```bash
   rm -rf ~/.local/share/nvim
   ```

2. **Install NvChad**  
   Clone the NvChad repository:
   ```bash
   git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1
   ```
   Launch Neovim and press `y` when prompted to install the default setup.

3. **Clone Custom Configurations**  
   Clone this repository, copy the contents of the folder, and paste them into the `lua/custom` directory (replacing the contents) in `~/.config/nvim`:
   ```bash
   git clone git@github.com:binayak9932/nvim_configs.git
   ```

4. **Restart Neovim**  
   Open Neovim again, and your custom configurations should now be loaded. Voilà!

4. **To change themes**
   
   press :`(space+T+H)`
   

---

Now your Neovim is set up with a personalized configuration. Enjoy!
