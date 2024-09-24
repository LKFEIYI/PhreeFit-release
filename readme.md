Here are the PhreeFit packages.
Initialization: unzip the compressed file and double-click the executable file: "PhreeFit(.exe)".

For Mac (M1/M2): you may see that a terminal with some information occurs with PhreeFit. Just ignore it and do not close it. Please wait a few minutes when starting for the first time, as your Mac might need to verify the security of software from unknown sources. Please try installing/updating the Xcode Command Line Tools if the software cannot be opened or the terminal reports any errors.
When the executable files (or compressed) are downloaded from the Internet, MacOS will add a head (com.apple.quarantine) to each file. Then, the files are considered unsafe.You can use teminal and input "cd" to enter the folder containing PhreeFit (folder) and MacosX (folder), which is like what we have done today, input cd and paste the full path of the folder behind cd.
Then, input "xattr -r -d com.apple.quarantine PhreeFit/" to remove those heads in the executable files. After that, you can double-click the PhreeFit executable file to start. For the first run, Mac will check and prepare the program. So you may wait for a few minutes.

I put two examples in the folder "example", including the titration data of acetic acid from Prof. Jeremy Fein and the titration data of an alkaline biochar (3-4 basic sites). The second example contains the raw titration data and the data ready for PhreeFit. It is recommended to use "simple_davies_for_titration.dat" for fitting titration data.
