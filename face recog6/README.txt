Running Eigenface.m from Matlab Command Prompt
==============================================

1. Extract "EigenFace.zip" Let us assume it has been installed in <CurrentDir> 

2. Open MATLAB

3. Set Current Directory to <CurrentDir>

4. In the command Window Type as below and press enter
	EigenFace('.\Train','LabelFile.txt','.\Test');

5. The output file is <CurrentDir>\Results.txt



Compiling Eigenface.m to create .exe file
=========================================

1. Extract "EigenFace.zip" Let us assume it has been installed in <CurrentDir> 

2. Open MATLAB

3. Set Current Directory to <CurrentDir>

4. Type the following and press enter
	mbuild -setup

5. Press Enter Again

6. Choose "Lcc C"

7. Press Enter Again

8. Type the following and press enter
	mcc -m EigenFace.m

9. This will build the EigenFace.exe file


Parameter Passing:
=================

3b.1 Open windows console by entering "cmd" from Start>Run in windows start menu.

3b.2 Change Directory to <CurrentDir>

3b.3 Type the following and press enter
	Eigenface.exe .\Train LabelFile.txt .\Test

4. The output file is <CurrentDir>\Results.txt
