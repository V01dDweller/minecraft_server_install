# Minecraft Server Install #

This is a basic ansible role that downloads and installs the Minecraft server jar into /opt/minecraft. It assumes Java is already installed.

```
minecraft_server_install
├── minecraft_install.yml
├── README.md
└── roles
    └── minecraft_server_install
        ├── files
        │   ├── eula.txt
        │   └── server.properties
        └── tasks
            └── main.yml
```
