# Guido for Windows

Find gRNAs in mosquito genomes from a simple desktop app: *Anopheles gambiae* (AgamP4 and idAnoGambNW_F1_1), *Culex pipiens* (idCulPipi1.1), or your own genome. Results include exon/intron annotation, filters, Excel output and an optional AgamP4 conservation score.

## [⬇ Download GuidoApp.exe](https://github.com/JavierArranzHerrero/GuidoApp/releases/latest/download/GuidoApp.exe)

## Install

**You need:** Windows 10 or 11, about 15 GB of free disk space, and [Docker Desktop](https://www.docker.com/products/docker-desktop/), which is free. You do not need a Docker account.

1. Install Docker Desktop, if you do not have it yet. If you skip this, Guido will offer to open its download page.
2. Download `GuidoApp.exe` and double-click it.
3. If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.
4. Choose whether you want a shortcut on your desktop.
5. Wait for the download (about 5 GB). This happens only once, and Guido then opens by itself.

The next time, open Guido from your desktop shortcut or the Start menu. You can delete the downloaded `GuidoApp.exe`.

## Use

Choose a genome, type a gene such as `AGAP008622`, and press **Run guido**. Excel files and plots are saved in `Documents\GuidoResults`.

## Problems?

- **Docker Desktop does not start:** open it yourself, accept its terms if it asks, wait until it is running, and open Guido again.
- **The download stopped:** check your internet connection and free disk space, then open Guido again. It continues where it stopped.
- **The progress bar is not moving:** this is normal during the largest part of the download.

## Linux and macOS

This app is for Windows only. On Linux and macOS, follow the instructions for [javiarranz/guido-webtool](https://hub.docker.com/r/javiarranz/guido-webtool) on Docker Hub.

## Credits

Designed by javierarranz. Powered by **guido**: Nace Kranjc & Courty Thomas (2023), *nkran/guido: v0.1.3*, Zenodo, https://doi.org/10.5281/zenodo.8056051
