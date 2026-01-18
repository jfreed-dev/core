# Home Assistant Core (Fork)

[![Chat Status](https://img.shields.io/discord/330944238910963714.svg)](https://discord.gg/c5DvZ4e)

This is a personal fork of [Home Assistant Core](https://github.com/home-assistant/core).

## Upstream Project

Open source home automation that puts local control and privacy first. Powered by a worldwide community of tinkerers and DIY enthusiasts.

- **Website:** [home-assistant.io](https://home-assistant.io)
- **Demo:** [home-assistant.io/demo](https://home-assistant.io/demo/)
- **Documentation:** [home-assistant.io/docs](https://home-assistant.io/docs/)
- **Developer Docs:** [developers.home-assistant.io](https://developers.home-assistant.io/)

## Installation

See the official [installation instructions](https://home-assistant.io/getting-started/).

## Development

```bash
# Clone this repo
git clone https://github.com/jfreed-dev/core.git
cd core

# Set up virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
pip install -r requirements_test.txt

# Run tests
pytest tests/
```

## Syncing with Upstream

```bash
git remote add upstream https://github.com/home-assistant/core.git
git fetch upstream
git merge upstream/dev
```

## License

Home Assistant is licensed under the [Apache License 2.0](LICENSE.md).
