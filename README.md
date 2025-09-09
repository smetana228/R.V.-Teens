# R.V. Teens – Gastronomic Project

R.V. Teens is a gastronomic project that aims to deepen the connection between restaurant administration and their customers.
The project provides a user-friendly website where restaurants can showcase their offerings and customers can engage in a more meaningful way.

## Installation & Setup (Using Open Server Panel)

1. **Install Open Server Panel**  
   - Download from [https://ospanel.io/](https://ospanel.io/).  
   - Install it to the default location (e.g., `C:\OSPanel`).  

2. **Create project folder**  
   Open a terminal/command prompt and run:  
   ```bash
   cd C:\OSPanel\home
   mkdir rvteens.local
   cd rvteens.local
3. **Create .osp configuration**
   ```bash
   mkdir .osp
   cd .osp
4. **Inside .osp, create a file named project.ini and add:**
   ```bash
   [rvteens.local]
5. **Copy/clone this repository into the C:\OSPanel\home\rvteens.local folder.**
6. **Start Open Server Panel**
   Right-click the OSPanel tray icon.
   You should now see rvteens.local at the top of the menu.
   Enable PHP, Nginx, and all required modules.
7. **Run the website at http://rvteens.local**
