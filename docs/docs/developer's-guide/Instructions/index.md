# Instructions

#### Development Installation
##### Linux
To set up a development environment, ensure you have `pip` installed (it may be packaged as `pip` or `pip3` on your system).
While it's possible to have Pulse working without setting up an virtual environment, it's strongly not recommended.
If you don't want to bother with virtual environments, you may want to look into [pipx](https://github.com/pypa/pipx).

1. Clone the repository:
```sh
git clone https://github.com/pulsepm/pulse
```

2. Navigate to the project directory:
```sh
cd pulse
```

3. Create and activate a virtual environment:
```sh
virtualenv venv --distribute && source venv/bin/activate
```

4. Install the required dependencies:
```sh
pip install -r requirements.txt
```

5. (Optional) Create a script for easier launching Pulse
Make sure `~/.local/bin` is in your `$PATH`.
```sh
echo "python3 $(pwd)/pulse.py \"\$@\"" > ~/.local/bin/pulse && chmod u+x ~/.local/bin/pulse
```
