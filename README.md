## Getting Started
This is a **minimal** template for a Rust project that uses [Hydro](http://github.com/hydro-project/hydro) for distributed services. To generate a project, run 

```bash
cargo install cargo-generate
cargo generate gh:sarahmorin/hydro-template
cd <myproject>
```

After `cd`ing into the workspace, run the sample tests

Then test the project:
```bash
cargo test
```

To learn more about the template, see the [Hydro Quickstart](https://hydro.run/docs/hydro/quickstart/first-dataflow).

## Project Structure
The template includes a sample program `temple`.

`template` demonstrates how to use Hydro to create dataflow programs for a distributed system, and can be launched by running `cargo run --example template`. Note the use of `--example` here because `src/bin/template.rs` contains the binary that will be launched for each process, whereas `examples/template.rs` contains a deployment script for connecting the processes together.

```bash
$ cargo run --example template
```
