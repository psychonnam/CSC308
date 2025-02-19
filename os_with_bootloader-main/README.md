# Rust OS

## Project Overview

**Rust OS** is a mini operating system developed in Rust, focusing on fundamental concepts of low-level system programming. This project includes a custom kernel, bootloader, and essential drivers, providing a solid foundation for understanding operating system development.

## Key Features

- **Custom Kernel**: Implements core OS functionalities including memory management, task switching, and interrupt handling.
- **Bootloader**: Initializes the OS and prepares the system for running the kernel.
- **Emulation**: Utilizes QEMU for testing and debugging, ensuring compatibility with x86_64 architecture.

## Technologies Used

- **Rust**: Programming language used for developing the OS components.
- **Bootloader**: Tool for initializing and loading the kernel.
- **QEMU**: Emulator for testing the OS on x86_64 architecture.

## How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/francisojeah/os_with_bootloader.git
   cd os_with_bootloader
   ```

2. **Build the Project**
   - Follow the instructions in the project to build the OS and bootloader.

3. **Run the OS**
   - Use QEMU to run the OS

## Contribution

Contributions are welcome! If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.
