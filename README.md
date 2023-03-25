# WJFallaoutParadiseAutoInstall

Please make sure you follow these steps to run the playbook:

Make sure you have Ansible installed on your system. If you don't have it installed, you can follow the official installation guide to install Ansible.
Create a directory for the playbook and save the provided YAML files in it. Organize the files as follows:

    lua

    playbook_directory/
    |-- main.yml
    |-- tasks/
        |-- install_packages.yml
        |-- install_lutris.yml
        |-- configure_wine_proton.yml
        |-- install_wabbajack.yml
        |-- install_modlist.yml

Open a terminal, navigate to the playbook directory, and execute the following command:

    bash

    ansible-playbook main.yml

The playbook will automate the process of installing the required packages, downloading and installing Lutris, configuring Wine and Proton, installing Wabbajack, and downloading and installing the modlist.

Please note that the provided playbook assumes you have already installed and configured Wine, as well as logged in to Steam to allow for the installation of Proton. If you need to perform additional steps or configurations, please let me know, and I can help you adjust the playbook accordingly.
