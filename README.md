### Compiling instructions ###

If you're installing on Mac make sure you have homebrew installed and command line tools installed.


1. Navigate to the source folder, change directory into the "build" folder: `cd build`

2. create make config files: `ccmake ..`

3. Hit `'c'` to configure. You'll see some random output, hit `'c'` again to configure. Hit `'g'` to generate make files therafter. 

4. Compile with the following command: `make -j2`. Note: the `-j` flag tells cmake how many CPUs to use

5. Check solver works by running test case