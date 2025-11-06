# PartIII-

practical for part III option Journey to the centre of the Earth

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sannecottaar/PartIII-practicals/HEAD)

## Setup

### VS Code

1. Via command pallet (Ctrl+Shift+P or Cmd+Shift+P) select "Git: Clone"
2. Paste the repository URL: <https://github.com/sannecottaar/PartIII-practicals.git>
3. Select the local directory where you want to clone the repository
4. Open the cloned repository in VS Code
5. Command pallet: "Python: Create Environment"
6. Select "Venv"
7. For interpreter select ~3.8-3.10
8. Select requirements.txt when prompted to install packages

### Command Line

 ```bash
 cd ~/Documents/ (or wherever you keep your code)
git clone https://github.com/sannecottaar/PartIII-practicals.git
cd PartIII-practicals
pip install virtualenv

virtualenv .venv
source .venv/bin/activate

pip install -r requirements.txt
 ```
