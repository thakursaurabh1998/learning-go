## What I learned with this program?

To run our go program we can opt one of the two ways:

- `go build`  
  This command builds our program lying in the current directory with all the other files.  
  After running the above command a new executable file is created which can be run and is platform independent(depends on how the build command was given). To run the executable write the following command:  
  
  `./first`
  > The name of the executable will be same as the name of the directory where it was built.

- `go run {filename}.go`  
  This command is really useful when we need to run small programs. It compiles the program and creates the executable in temporary directory of the system and runs it directly from there.