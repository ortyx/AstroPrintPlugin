project(AstroPrintPlugin NONE)
cmake_minimum_required(VERSION 2.8.12)

install(FILES
    __init__.py
    plugin.json
    DiscoverAstroPrintAction.py
    DiscoverAstroPrintAction.qml
    AstroPrintComponents.qml
    AstroPrintOutputDevice.py
    AstroPrintOutputDevicePlugin.py
    MonitorItem.qml
    LICENSE
    README.md
    DESTINATION lib/cura/plugins/AstroPrintPlugin
)
