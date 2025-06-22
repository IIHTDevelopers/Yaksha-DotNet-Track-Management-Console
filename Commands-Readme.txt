* Install the .NET SDK 6.0 by running:
	sudo apt install dotnet-sdk-6.0
	- If it asks for the password, provide password : pass@word1 

	 - If it asks: Do you want to continue? [Y/n]
		Type Y and press Enter.

* On command prompt, cd into your project folder (cd <Your-Project-folder>).

* To build your project use command:
	( TrackManagement / dotnet build)

* To launch your application, Run the following command to run the application:
	( TrackManagement / dotnet run)

* To run the test cases in CMD, Run the following command to test the application:

	(TrackManagement.Tests/dotnet test --logger "console;verbosity=detailed")

 (You can run this command multiple times to identify the test case status,and   refactor code  to make maximum test cases passed before final submission).
