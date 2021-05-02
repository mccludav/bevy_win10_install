![](img/banner.svg)
# Screenshot Installation of Bevy with Rust on Windows 10
Visual Guide for Installing Bevy with Rust on a Windows 10 Machine

### Installing Rust
1.	Navigate to https://github.com/bevyengine/bevy.

![](img/step01.png)

2.	Scroll down to Docs and click on The Bevy Book.

![](img/step02.png)

3.	Click on Setup.
	
![](img/step03.png)

4.	Click on Rust Getting Started Guide.

![](img/step04.png)

5.	Click on DOWNLOAD RUSTUP-INIT.EXE (64-BIT).

![](img/step05.png)

6.	Click on the up arrow 

![](img/step06.png)

7.	and select Open.

![](img/step07.png)

8.	If this window pops-up, select More info.

![](img/step08.png)

9.	Select Run anyway.

![](img/step09.png)

10.	Type 1 [Enter] for default installation.

![](img/step10.png)

11.	Press [Enter] to continue.

![](img/step11.png)

### Installing VS2019 Build Tools
12.	Back at https://bevyengine.org/learn/book/getting-started/setup/ select VS2019 build tools

![](img/step12.png)

13.	Press the down arrow shown,

![](img/step13.png)

14.	and select Open.

![](img/step14.png)

15.	Select Yes to install

![](img/step15.png)

16.	Press Continue.

![](img/step16.png)

17.	Select Install.

![](img/step17.png)

18.	When complete, close the window.

![](img/step18.png)

### Run a Rust Program
19.	Type Command Prompt in search field of task bar.

![](img/step19.png)

20.	Click on Command Prompt App.

![](img/step20.png)

21.	In the Command Prompt window, type cd c:\

![](img/step21.png)

22.	Next type mkdir Rust [Enter], followed by cd Rust [Enter].

![](img/step22.png)

23.	Type cargo new my_bevy_game [Enter], followed by cd my_bevy_game [Enter].

![](img/step23.png)

24.	Type cargo run.

![](img/step24.png)

### Add Bevy to Project’s Cargo.toml
25.	Type Visual Studio Code in the search window and select the App.

![](img/step25.png)

26.	Select File drop down menu and Open Folder.

![](img/step26.png)

27.	Navigate to my_bevy_game sub-directory and click on Select Folder.
	
![](img/step27.png)

28.	Open Cargo.toml file and add in [dependencies]

![](img/step28.png)

29.	Add below [dependencies], line 10, bevy = “0.5” # verify version at https://crates.io/crates/bevy.  Ensure at the shown website that 0.5 is the latest release, if not, then set bevy to the release number.  Type a Ctrl-S to save file Cargo.toml.

![](img/step29.png)

30.	Again, in the Command Prompt window type cargo run [Enter].  It will take a while to download and compile the dependencies.

![](img/step30.png)

31.	For more information and further steps refer to https://bevyengine.org/learn/book/getting-started/setup/.

![](img/step31.png)
