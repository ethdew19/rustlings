<div class="oranda-hide">

# Rustlings 🦀❤️

</div>

Greetings and welcome to Rustlings.
This project contains small exercises to get you used to reading and writing Rust code.
This includes reading and responding to compiler messages!

It is recommended to do the Rustlings exercises in parallel to reading [the official Rust book](https://doc.rust-lang.org/book/), the most comprehensive resource for learning Rust 📚️

[Rust By Example](https://doc.rust-lang.org/rust-by-example/) is another recommended resource that you might find helpful.
It contains code examples and exercises similar to Rustlings, but online.

## Getting Started

### Installing Rust

Before installing Rustlings, you need to have _Rust installed_.
Visit [www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install) for further instructions on installing Rust.
This'll also install _Cargo_, Rust's package/project manager.

🐧 If you're on Linux, make sure you've installed `gcc` (for a linker). Deb: `sudo apt install build-essential gcc`. Dnf: `sudo dnf install gcc`.

🍎 If you're on MacOS, make sure you've installed Xcode and its developer tools by typing `xcode-select --install`.

### Installing Rustlings

The following command will download and compile Rustlings:

<!-- TODO: Remove @6.0.0-beta.x -->

```bash
cargo install rustlings@6.0.0-beta.3
```

<details>
<summary>

**If the installation fails…** (_click to expand_)

</summary>

<!-- TODO: Remove @6.0.0-beta.x -->

- Make sure you have the latest Rust version by running `rustup update`.
- Try adding the `--locked` flag: `cargo install rustlings@6.0.0-beta.3 --locked`
- Otherwise, please [report the issue](https://github.com/rust-lang/rustlings/issues/new).

</details>

### Initialization

After installing Rustlings, run the following command to initialize the `rustlings/` directory:

```bash
rustlings init
```

Now, go into the newly initialized directory and run Rustlings for further instructions on getting started with the exercises:

```bash
cd rustlings/
rustlings
```

## Doing exercises

The exercises are sorted by topic and can be found in the subdirectory `exercises/<topic>`.
For every topic, there is an additional `README.md` file with some resources to get you started on the topic.
We highly recommend that you have a look at them before you start 📚️

Most exercises contain an error that keeps them from compiling, and it's up to you to fix it!
Some exercises contain tests that need to pass for the exercise to be done.

### Watch Mode

To run the exercises, launch Rustlings:

```bash
rustlings
```

This will start the _watch mode_ which walks you through the exercises in a predefined order (what we think is best for newcomers).
It will rerun the current exercise automatically every time you change the exercise's file in the `exercises/` directory.

<details>
<summary>

**If detecting file changes in the `exercises/` directory fails…** (_click to expand_)

</summary>

You can add the `--manual-run` flag (`rustlings --manual-run`) to manually rerun the current exercise by entering `r` or `run` in the watch mode.

Please [report the issue](https://github.com/rust-lang/rustlings/issues/new) with some information about your operating system and whether you run Rustlings in a container or virtual machine (e.g. WSL).

</details>

### Exercise List

In the [watch mode](#watch-mode) (after launching `rustlings`), you can enter `l` or `list` to open the interactive exercise list.

The list allows you to…

- See the status of all exercises (done or pending)
- `c`: Continue at another exercise (temporarelly skip some exercises or go back to a previous one)
- `r`: Reset the status and file of an exercise (you need to reload/reopen its file in your editor afterwards)

See the footer of the list for all possible keys.

## Continuing On

<!-- TODO: Mention third-party exercises -->

Once you've completed Rustlings, put your new knowledge to good use!
Continue practicing your Rust skills by building your own projects, contributing to Rustlings, or finding other open-source projects to contribute to.

## Uninstalling Rustlings

If you want to remove Rustlings from your system, run the following command:

```bash
cargo uninstall rustlings
```

That's it!

## Contributing

See [CONTRIBUTING.md](https://github.com/rust-lang/rustlings/blob/main/CONTRIBUTING.md) 🔗

## Contributors ✨

Thanks to [all the wonderful contributors](https://github.com/rust-lang/rustlings/graphs/contributors) 🎉
