# Fork "Savant: High-Performance Computer Vision Framework For Data Center And Edge"
https://github.com/insight-platform/Savant

# Изменения

1. Изменения реализованы на основании ветки "releases/0.2.11"
1. Для сборки образа savant-adapters-py  используется 3.10.13-slim-bullseye

# Сборка образа

``make -f Makefile build-adapters-py``

Если необходимо жестко задать целевую платформу, то

``make -f Makefile build-adapters-py PLATFORM="linux/arm64"``
