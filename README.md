# Password Manager

Generate strong random passwords (copied to clipboard automatically), save them per website, and search them later. Built with Tkinter.

> ⚠️ This is a learning project: passwords are stored **unencrypted** in `~/Library/Application Support/Password Manager/data.json`. Don't use it for real accounts.

Built with Python while learning (part of my [PythonProject](https://github.com/kunal-dangi/PythonProject) 100-days journey).



## Download (macOS)

Grab the **.dmg** from the [latest release](https://github.com/kunal-dangi/password-manager/releases/latest), open it, and drag **Password Manager** into Applications.

The app isn't notarized by Apple, so the first launch will be blocked. Either right-click the app → **Open**, or run:

```bash
xattr -cr "/Applications/Password Manager.app"
```

Built for Apple Silicon (arm64) Macs.

## Run from source

```bash
pip install -r requirements.txt
python3 main.py
```

## Build the DMG yourself

```bash
pip install pyinstaller -r requirements.txt
./build.sh
```
