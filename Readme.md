# MPC Video Renderer

MPC Video Renderer is a free and open-source video renderer for DirectShow. The renderer can potentially work with any DirectShow player, but full support is available only in the MPC-BE. Recommended MPC-BE 1.6.5.164 (8e684d199) or newer.

## Minimum system requirements

* An SSE2-capable CPU
* Windows 7¹ or newer
* DirectX 9.0c video card

¹For Windows 7, you must have D3DCompiler_47.dll file. It can be installed via update KB4019990.

## Recommended system requirements

* An SSE2-capable CPU
* Windows 8.1 or newer
* DirectX 10/11 video card

## Installation

1. Download the release archive (`.zip`) from the [releases page](https://github.com/Aleksoid1978/VideoRenderer/releases).
2. Create a folder in any permanent location (for example, next to your player or application executable, such as `MpcVideoRenderer\` in the same directory as your player).
3. Extract the contents of the archive into that folder. The folder will contain:
   - `MpcVideoRenderer.ax` — 32-bit filter
   - `MpcVideoRenderer64.ax` — 64-bit filter
   - `Install_MPCVR_32.cmd` / `Install_MPCVR_64.cmd` — installation scripts
   - `Uninstall_MPCVR_32.cmd` / `Uninstall_MPCVR_64.cmd` — uninstallation scripts
4. Right-click `Install_MPCVR_64.cmd` (for 64-bit systems) or `Install_MPCVR_32.cmd` (for 32-bit systems) and choose **Run as administrator**.

> **Important:** Do not move or delete the `.ax` file after installation. The installer registers the filter at its current location. If you move the file later you must uninstall and reinstall from the new location.

To uninstall, right-click the matching `Uninstall_MPCVR_*.cmd` script and choose **Run as administrator**.

## License

MPC Video Renderer's code is licensed under [GPL v3].

## Links

Nightly builds - <https://yadi.sk/d/X0EVMKP4TcmnHQ>

Topic in MPC-BE forum (Russian) - <https://mpc-be.org/forum/index.php?topic=381>

MPC-BE - <https://sourceforge.net/projects/mpcbe/>

## Donate

<https://mpc-be.org/forum/index.php?topic=240>
