# procstat
A simple python script that list all open port of a process

## Usage

* Using the PID

      procstat -p <PID>
 
* Using the process name

      procstat -n <PROCESS NAME>

* Usage message

      procstat -h
 
 ## Installation

Fedora

    sudo dnf install gcc python-devel
    sudo pip3 install psutil

Ubuntu

    sudo apt install gcc python-dev
    sudo pip3 install psutil

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
