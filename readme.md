# FastAPI AI Photo Generator


To add support for `.heic` images (e.g. iPhone images) install `libheif` via [homebrew](https://brew.sh):
```bash
brew install libheif
(venv) python -m pip install pillow-heif
```
If on _linux_ or _Docker_, you can use `sudo apt-get install libheif-dev`