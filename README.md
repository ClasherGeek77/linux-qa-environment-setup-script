# Linux QA Environment Setup Scripts 🛠

A collection of fully automated shell scripts engineered to instantly provision Linux environments (specifically Ubuntu) with the entire toolchain required for a QA Automation Engineer.

## 🎯 Objective
To eliminate the "It works on my machine" problem and reduce QA onboarding time from hours down to minutes by programmatically installing all dependencies.

## 📦 What gets installed?
- **Android Tools**: `install-adb.bash`, `install-android-sdk.bash`, `bundletool-all-1.9.1.jar`
- **Automation frameworks**: `install-appium-and-appium-inspector.bash`, `install-appium-only.bash`
- **Browsers**: `install-chrome-dev.bash`, `install-dedicated-chrome.bash`
- **Infrastructure**: `install-docker-engine.bash`, `install-docker-compose-1.25.1.bash`, `install-genymotion.bash`
- **Development Environment**: `install-github-desktop.bash`, `install-pyenv.bash`, `install-virtualenv.bash`, `setup-python39.bash`

## 🚀 Usage
```bash
# Example: Installing Docker Engine
chmod +x install-docker-engine.bash
./install-docker-engine.bash
```

> *"I don't just automate tests. I build testers."* — Teddy Lioner
