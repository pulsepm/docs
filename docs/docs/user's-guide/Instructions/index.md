# Instructions

### Installation guide

#### Linux
##### Install Script (Recommended)
Execute the script to install (or update if necessary) `pulse`.
```sh
wget -qO- https://raw.githubusercontent.com/pulsepm/pulse/master/install.sh | bash -s
```

##### Manual Installation
1. Download the latest version of Pulse from our [releases](https://github.com/pulsepm/pulse/releases).

2. Mark the downloaded binary as executable:
```sh
chmod u+x pulse
```

3. (Optional) Move it to a location that's defined in your `$PATH`:
```sh
mv pulse /usr/local/bin/ # sudo permissions are required by this specific path
```
