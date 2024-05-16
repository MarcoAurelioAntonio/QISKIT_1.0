<img src="https://avatars.githubusercontent.com/u/30696987?s=200&v=4" alt="Qiskit" style="background-color: white; padding: 5px;">

# Quick Start with Qiskit 1.x

Qiskit 1.0 brings new stability guarantees and performance improvements, but it does break compatibility with all previous versions of Qiskit

This repository contains basic instructions to get started with Qiskit in a virtual environment.
[For more information clik here](https://docs.quantum.ibm.com/start/install)

## Setting up Virtual Environment USING MINICONDA 3

1. **Create a virtual environment with Conda:**

    ```shell
    conda create --name beginning
    ```

    This will create a virtual environment named `beginning`.

2. **Activate the virtual environment:**

    ```shell
    conda activate beginning
    ```

    This will activate the `beginning` virtual environment, where we will install the Qiskit libraries.

## Installing Qiskit and its Dependencies

1. **Install pip (if not already installed):**

    ```shell
    conda install pip
    ```

    Pip is the package management system for Python and will be necessary for installing additional libraries.

2. **Install Qiskit:**

    ```shell
    pip install qiskit
    ```

    Qiskit is an open-source quantum computing library that provides tools for working with quantum circuits.

3. **Install Matplotlib (optional, but recommended for visualizations):**

    ```shell
    pip install matplotlib
    ```

    Matplotlib is a 2D plotting library for Python.

4. **Install Qiskit IBM Runtime (optional, for accessing IBM Quantum resources):**

    ```shell
    pip install qiskit_ibm_runtime
    ```

    This library provides access to IBM Quantum cloud computing resources, If you plan to run jobs on quantum hardware.

5. **Install Qiskit visualization, extra visualization support**

    ```shell
    pip install qiskit[visualization]
    ```

6. **Cloning an environment**

    Use the terminal for the following steps:

    ```shell
    conda create --name myclone --clone myenv
    ```
    You can make an exact copy of an environment by creating a clone of it

    Replace `myclone` with the name of the new environment. Replace `myenv` with the name of the existing environment that you want to copy.

   - This is going to happen

   ![9868f14b-914a-48bd-abc1-e26a40768e49](https://github.com/MarcoAurelioAntonio/QISKIT_1.0/assets/99001924/7146834b-ed3f-44b4-a7b7-8483c0f2b00f)




## :blue_book: Acknowledgements
- This code is based on the documentation provided by [IBM Quantum Documentation Web.](https://docs.quantum.ibm.com/start/install)

## :handshake: Contributing
- I welcome collaboration and contributions to improve this code and Doc. Feel free to fork and submit pull requests or Add a new issue with your suggestions.

## 📝 License

This project is [MIT](./LICENSE) licensed.
