# create a project with cargo
`cargo new <project_name>`

# building and running a cargo project
`cargo build`

## This command creates an executable file in target/debug/hello_cargo (or target\debug\hello_cargo.exe on Windows) rather than in your current directory. Because the default build is a debug build, Cargo puts the binary in a directory named debug. You can run the executable with this command:
`./target/debug/hello_cargo`

## we can also use cargo run to compile the code and then run the resultant executable all in one command:
`cargo run`

## Cargo also provides a command called cargo check. This command quickly checks your code to make sure it compiles but doesn’t produce an executable:
`cargo check`

## many Rustaceans run cargo check periodically as they write their program to make sure it compiles. Then they run cargo build when they’re ready to use the executable.

# building for release

## This command will create an executable in target/release instead of target/debug.
`cargo build --release`