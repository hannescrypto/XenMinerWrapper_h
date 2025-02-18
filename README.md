hannescrypto modded version 
changes

1.) shows CPU cores/threads (and now you can select the threads not the cores)

2.) show CPU Load/Mem Load (sadly only update on Startup) 

3.) store all userfiles incl. Loaction of miner.py in userdata folder

4.) works with newest miner.py but weird output because of new colorscheme in miner.py

5.) made the window wider so no problems with the miner text splitet up in 2 rows





Date 21.09.2023








# XEN.pub's XenMiner Wrapper

Welcome to the XEN.pub's XenMiner Wrapper, a Python-based user interface for XenMiner. This tool simplifies the process of setting up and running the XenMiner by providing a user-friendly interface that seamlessly works across Linux, macOS, and Windows.

## Features

1. **User-Friendly Interface**: No need to tinker with the code or command line. Set your Ethereum address and other options directly from the UI.
2. **Automatic Script Update**: The application fetches the latest version of Jack's XenMiner script from GitHub every time you press the Run button, ensuring you're always using the most recent and optimized version.
3. **Ethereum Address Swap**: Automatically replaces Jack's Ethereum address with yours, ensuring that mining rewards go directly to your account.
4. **One-Click Execution**: Run the miner script (as many times as your computer can handle) with just one click.
5. **Parallel Execution**: Execute the miner as many times as the physical CPU cores on your computer, maximizing your mining potential.
6. **Cross-Platform**: Written in Python, this tool is platform-independent and should be able to run on Windows (confirmed), Linux (Ubuntu confirmed) and macOS.
7. **Block Counter Support**: Counts total of all minted blocks across all threads.

## Getting Started

1. Ensure you have Python 3.x and pip3 installed on your system.
2. Then pip install -U -r requirements.txt
3. Clone or download the repository.
4. Run the `XenMiner UI Wrapper` script.
5. Enter your Ethereum address, enter the path to your Python executable and select other options as needed.
6. Click on the "Run" button to start mining.

## Demo

A video demo of the XenMiner UI Wrapper in action:

https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/e4c9240f-fe0d-450b-aaa4-749b9c52f6e3


## Screenshots:

Windows | Ubuntu |  Mac

[<img src="https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/7ea6253e-758e-43cc-b825-90c4efee0999" width="200" height="150" alt="Windows">](https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/7ea6253e-758e-43cc-b825-90c4efee0999)
[<img src="https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/39feb6ba-ce7a-4ec8-96e0-b379fd628763" width="200" height="150" alt="Ubuntu">](https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/39feb6ba-ce7a-4ec8-96e0-b379fd628763)
[<img src="https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/2554b79f-20d1-42a5-ae70-521fb8fcd8f0" width="200" height="150" alt="Ubuntu">](https://github.com/JozefJarosciak/XenMinerWrapper/assets/3492464/2554b79f-20d1-42a5-ae70-521fb8fcd8f0)

## Acknowledgments

This UI wrapper for XenMiner was developed to enhance the user experience and make mining more accessible to everyone. The original XenMiner script that this wrapper leverages was created by Jack Levin (https://github.com/jacklevin74/xenminer).
The UI and integration are Xen.pub's contributions to this open-source project.

Find me or contact me on Twitter: [https://twitter.com/jarosciak](https://twitter.com/jarosciak)

Or on our website: https://Xen.pub

## License

This project is open-source. Please refer to the `LICENSE` file for more details.
