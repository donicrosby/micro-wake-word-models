# Models

These are my custom models I have trained

##  Usage

To use, you must take control (or adopt) your ESPHome voice assistant and add the following to the YAML:

micro_wake_word:
  models:
    - model: "URL of the model JSON file"

For example:

micro_wake_word:
  models:
    - model: "https://raw.githubusercontent.com/donicrosby/micro-wake-word-models/refs/heads/main/models/hey_rj.json"

After rebuilding the ESPHome firmware and updating the device, visit its device info page in Home Assistant to change the active wake word.

## Training
These models were trained with this [notebook](https://github.com/ClarePhang/MicroWakeWord-Trainer-Docker/blob/main/advanced_training_notebook.ipynb) using the default settings.