# Amaysim
Test Automation for My Amaysim Manage Settings functionality


In order to run this automation you need to do the following:

1. Install the following:

	A. Download and install Ruby
	B. Download and Install Devkit
	C. Install Cucumber and other Ruby Gems. Before installing cucumber, update first the gem setup. Run this 	command, gem update -- system
	D. Install the other needed Gems. Run this command
	gem install -- no-ri -- no-rdoc rspec cucumber

2. Initialize cucumber so the following folders will be created, features, step_definitions and support. Execute this command, cucumber --init


3. Make sure you have Google Chrome browser installed in your machine. If Google Chrome is not installed in you machine, you need to download and install it.



4. Install the Bundler. Open command prompt and type gem install bundler. Then hit enter.



5. Download and extract chromedriver.
	A. Download and Extract the file. Copy the location where you extract the file. Example: C:\Users\you\Documents\DVC Files\03. Other Files\01. Ruby\chromedriver_win32.
	B. Make sure to indicate the path of the chromedriver_win32 in Environment System variable. Do the following:
		- The go to Start – Right-click on Computer then select Properties. Click on Advance system settings:
		- Click Advance Tab
		- Click Environment Variables button
		- Locate the Path variable under System Variables. Select the Path variable and click Edit… button
		- Go to the end of the path and add ; then enter the path of the chrome driver.Then click OK


6. Before running the script check the following on the site
	A. SIM Nickname should not be Pedro
	B. Recharge Pin should not be 1234
	C. Called ID checkbox should be unchecked
	D. Call Waiting checkbox should be unchecked
	E. Voicemail checkbox should be unchecked
	F. Usage alerts checkbox should be unchecked
	G. International Roaming checkbox should be unchecked



7. Running the scripts
	A. Make sure all files needed are avaiable.
	B. Open command Prompt
	C. Change directory to where the files were saved
	D. Type "cucumber features\Manage_Settings.feature TEST_ENV = PROD or QA depending on where you would like to run the script
	E. Hit Enter



	