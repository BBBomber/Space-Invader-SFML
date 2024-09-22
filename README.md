# Space-Invader-SFML

A classic **Space Invader** game made using **SFML** in C++.

## Prerequisites

To run this project, you will need to install the following:

- **SFML** (Simple and Fast Multimedia Library) for C++.
- Download the latest **x64 SFML** version for Windows from the official SFML website: [SFML Download](https://www.sfml-dev.org/download/sfml/2.5.1/).

## Setup Instructions

Follow these steps to get the game up and running:

### 1. Download SFML

1. Download the latest **x64 version** of SFML for Windows from the SFML website.
2. Extract the contents of the downloaded SFML zip file.

### 2. Set Up SFML in the Project

1. **Copy and paste the `lib` and `include` folders** from the downloaded SFML directory to the **`SFML` folder** in this project directory.
   - Navigate to the downloaded SFML folder.
   - Copy the `lib` and `include` directories.
   - Paste them into the **`SFML`** folder of this project.

### 3. Build and Run the Project in Debug Mode

1. Open the project in your preferred IDE (such as Visual Studio).
2. Ensure the project is set to **Debug Mode** and build the project once.
3. This will generate an **x64 directory** within your project.

### 4. Set Up the SFML DLLs

1. Go to the **`bin` folder** of the SFML directory you downloaded.
   - Example path: `C:/path-to-sfml/SFML-2.5.1/bin/`
2. Copy all the DLL files from the `bin` folder.
3. Paste these DLL files into the generated **x64/Debug** directory of your project.
   - Example path: `YourProject/x64/Debug/`

### 5. Run the Game

Now, after copying the required DLLs into the x64/Debug folder, the project should run successfully.

Open the project in your IDE and press **Run** to start playing the **Space Invader** game!

---

## Troubleshooting

- Ensure that you're using the **x64** version of SFML.
- Verify that you've copied both the `lib`, `include` folders into the `SFML` folder within the project directory.
- Ensure that all DLLs from the SFML `bin` folder are correctly placed in the generated `x64/Debug` folder.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

## Acknowledgements

- Developed using the **SFML (Simple and Fast Multimedia Library)**.
- Special thanks to the open-source community for continuous support.

Enjoy playing the classic Space Invader game!
