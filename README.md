# Interview - Cherrytree

Cherrytree is a hierarchical note-taking application featuring rich text and syntax highlighting, storing data in a single XML or SQLite file. It is available for Linux, Windows, and macOS.

## Installation

- **Download:** You can download Cherrytree from the [official website](https://www.giuspen.net/cherrytree/#downl).

- **Flatpak/Snap:** Alternatively, you can install the latest version of Cherrytree (1.0.4) using Flatpak or Snap. These package managers offer the most up-to-date versions of Cherrytree, ensuring compatibility and access to new features.

- **Linux Repositories:** Be cautious when using regular repositories, as they may offer older versions of Cherrytree that could be incompatible with your files.

## Getting Started

Before opening your Cherrytree document ('<b>knowledge_base_devops.ctb</b>'), ensure you import the preferences file('cherrytree_preferences.cfg'):
1. Open Cherrytree.
2. Go to `File` > `Preferences`.
3. Select `Import Preferences`.
## Running in Docker (Linux Users)

You can also run Cherrytree 1.0.4 within a Docker container, where both your Cherrytree document and preferences file are pre-loaded:

1. Pull the Docker image manually from Docker Hub:
   ```bash
   docker pull leoncz/cherry:latest

2. Allow connection to the X11 server:
   ```bash
   xhost +local:docker

3. Start the container using Docker Compose:
   ```bash
   docker-compose up

