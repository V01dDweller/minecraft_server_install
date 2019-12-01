# Minecraft Server 1.14.4 Install #

This is a basic ansible playbook and role, intended for Linux, that
downloads and installs the Minecraft server jar into /opt/minecraft. It
assumes Java is already installed.

```
minecraft_server_install
├── minecraft_install.yml
├── README.md
└── roles
    └── minecraft_server_install
        ├── files
        │   ├── eula.txt
        │   └── server.properties
        ├── meta
        │   └── main.yml
        └── tasks
            └── main.yml
```
