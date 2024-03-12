# How to Setup Python and Pygame (Properly)
Using Anaconda Navigator allows you to create "Environments" that contain Python packages and is seperate from your main system. This means you can uninstall Anaconda Navigator when finished with this module and it will also remove all the Python packages you installed. It's also useful for managing the Python packages you have and controlling their versions.

1. Download Anaconda Navigator from the [offical site](https://www.anaconda.com/download).
2. Install Anaconda Navigator. // Make sure you tick to also install Anaconda Prompt if given the option.
3. Open Anaconda Navigator and select Environments from the left pane. You will only see "base (root)" (I have some already).
<div align="center">
  <a href="Images\Anaconda Nav.png" target="_blank">
    <img src="Images\Anaconda Nav.png" style="height:400px;"/>
  </a>
</div>
<br>

4. Give the environment a name (e.g PygameEnv). Select the version of Python you want -- the most recent one should be fine. Press Create.
<div align="center">
  <a href="Images\Create new environment.png" target="_blank">
    <img src="Images\Create new environment.png" style="height:200px;"/>
  </a>
</div>
<br>

5. Selecting your environment and setting the dropdown to the right of this to "Installed" will show all the Python packages in this environment. You will have some installed by default (for me it has downloaded 17).

<div align="center">
  <a href="Images\Environment.png" target="_blank">
    <img src="Images\Environment.png" style="height:400px;"/>
  </a>
</div>
<br>

6. Keep Anaconda Navigator open. Open command prompt and select to make changes to your environment by typing (swap YourEnvNameHere with your env):
<br><br>`conda activate YourEnvNameHere`
<br><br>You will notice that the part in brackets has changed from "root" to your environment (see below screenshot).

7. As found at the [PyPi site](https://pypi.org/project/pygame/) (often used by developers for hosting Python packages), paste the command to install Pygame:
<br><br>`pip install pygame`

<div align="center">
  <a href="Images\Terminal.png" target="_blank">
    <img src="Images\Terminal.png" style="height:300px;"/>
  </a>
</div>
<br>
<div align="center">
  <a href="Images\Installed.png" target="_blank">
    <img src="Images\Installed.png" style="height:300px;"/>
  </a>
</div>
<br>

8. Now, if you check your environment in Anaconda Navigator, select Update Index, you will see Pygame is included in the install packages:
<br> 
<div align="center">
  <a href="Images\Installed Anaconda Nav.png" target="_blank">
    <img src="Images\Installed Anaconda Nav.png" style="height:400px;"/>
  </a>
</div>
<br>

9. Finally, if you're using VS Code (I recommend you do), select the option at the bottom right or maybe bottom left on Windows to bring up the options to select a Python interpreter at the top of the screen and select your environment:

<br> 
<div align="center">
  <a href="Images\VS Code.png" target="_blank">
    <img src="Images\VS Code.png" style="height:400px;"/>
  </a>
</div>
<br>