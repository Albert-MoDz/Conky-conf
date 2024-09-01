## Conky-Conf

Welcome to my Conky configuration repository for Linux! 🎉

### Screenshot

Here is a screenshot of the Conky setup using this configuration:

![Conky Screenshot]([images/Conky-Cap.png](https://github.com/Albert-MoDz/Conky-conf/blob/main/Conky-Cap.png))

### Overview

This repository contains a custom configuration for Conky, a lightweight system monitor tool for Linux. Conky is highly customizable, and this configuration file is designed to provide a comprehensive and visually appealing display of system information.

### Features

- **System Information**: Displays essential information about your system, including CPU, GPU, memory, disk usage, and network activity.
- **Real-Time Monitoring**: Shows live data updates, such as CPU usage, memory usage, and network speeds.
- **Customizable Layout**: The configuration supports multiple bars or sections, allowing you to arrange the system information according to your preferences.
- **Visual Appeal**: Uses custom fonts, colors, and spacing to create an aesthetically pleasing and organized display.

### Installation

To use this Conky configuration, follow these steps:

1. **Download or Clone the Repository**:
   - Clone this repository to your local machine using Git:
     ```sh
     git clone <repository-url>
     ```
   - Or download the ZIP file and extract it to a directory of your choice.

2. **Create the Configuration File Path**:
   - Navigate to your home directory and create the necessary directories if they do not already exist:
     ```sh
     mkdir -p ~/.config/conky
     ```
   - Copy the `conky.conf` file from this repository into the newly created directory:
     ```sh
     cp /path/to/downloaded/conky.conf ~/.config/conky/conky.conf
     ```

3. **Adjust the Configuration**:
   - Open `~/.config/conky/conky.conf` in your preferred text editor:
     ```sh
     nano ~/.config/conky/conky.conf
     ```
   - Customize any settings as needed, such as alignment, colors, or the layout of the bars. Adjust the paths, colors, fonts, and any other settings to match your preferences.

4. **Run Conky**:
   - Ensure Conky is installed on your system. You can install it using your package manager:
     ```sh
     sudo apt-get install conky  # For Debian-based systems
     sudo yum install conky      # For Red Hat-based systems
     sudo pacman -S conky        # For Arch-linux systems
     ```
   - Start Conky with your configuration:
     ```sh
     conky -c ~/.config/conky/conky.conf
     ```

### Configuration Details

- **File Path**: `/home/your-username/.config/conky/conky.conf`
  - Replace `your-username` with your actual username on your Linux system.

- **Configuration Highlights**:
  - The configuration file includes sections for system information, CPU usage, GPU usage, memory usage, disk usage, network statistics, and top processes.
  - Customizable layout and color schemes to fit your personal style.

### License

This project is licensed under the GNU General Public License Version 3, 29 June 2007. See the [LICENSE](LICENSE) file for details.

