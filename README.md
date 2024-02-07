# Flatpak for wxEDID

wxEDID is a wxWidgets - based EDID (Extended Display Identification Data) editor. For more information, please [visit the project website](https://sourceforge.net/projects/wxedid/).

This software is flaky, by running it repeatedly the window may appear eventually:

```bash
flatpak run --file-forwarding net.sourceforge.wxEDID @@ '/home/user/path/to/edid_file.bin' @@
```
