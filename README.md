# CMDMachine: Command Line Drum Machine

CMDMachine is a lightweight and powerful drum machine that runs directly from your command line. Designed for musicians, producers, and hobbyists alike, CMDMachine allows you to create and manipulate drum patterns quickly and efficiently without the need for a GUI. Perfect for those who prefer a terminal-based workflow, CMDMachine offers an intuitive and flexible way to craft beats on the fly.

## Features

- **Easy-to-Use Command Line Interface**: Simple and intuitive commands to create, edit, and play drum patterns.
- **Flexible Pattern Creation**: Define patterns with various time signatures and subdivisions.
- **Wide Range of Drum Sounds**: Includes a library of high-quality drum samples.
- **Real-Time Playback**: Play your patterns in real-time with adjustable tempo.
- **Pattern Export**: Export your creations to popular audio formats for further use in DAWs.
- **Scriptable**: Automate your workflow with scripts to generate complex rhythms and sequences.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.

## Installation

To install CMDMachine, ensure you have Python 3.6 or higher installed, then use pip to install:

```bash
pip install cmdmachine
```

## Usage

Start CMDMachine by typing `cmdmachine` in your terminal:

```bash
cmdmachine
```

### Basic Commands

- **Create a New Pattern**: 
  ```bash
  create pattern <pattern_name>
  ```
- **Add Drum Sound to Pattern**: 
  ```bash
  add sound <pattern_name> <drum_sound> <position>
  ```
- **Play Pattern**: 
  ```bash
  play <pattern_name>
  ```
- **List Available Drum Sounds**: 
  ```bash
  list sounds
  ```

### Example

Create a basic 4/4 kick and snare pattern:

```bash
cmdmachine
create pattern basic_beat
add sound basic_beat kick 1,5,9,13
add sound basic_beat snare 5,13
play basic_beat
```

## Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding new features, or improving documentation, your help is appreciated. Please check out our [contribution guidelines](CONTRIBUTING.md) for more information.

## License

CMDMachine is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please open an issue on our [GitHub repository](https://github.com/sochiyuzuki/cmdmachine).

---

CMDMachine - Bringing beats to your terminal.
