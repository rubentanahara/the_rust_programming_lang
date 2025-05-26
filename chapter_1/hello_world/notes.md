### Commands

This command create an executable file on **target/debug/hello_world**
```bash
cargo build
```

You can run the executable with this command
```bash
./target/debug/hello_world
```

To compile and run in one command
```bash
cargo run
```
This command quickly checks your code to make sure it compiles but does not produce and executable
```bash
cargo check
```

Building for release, this will be save on **./target/release**
```bash
cargo build --release
```
