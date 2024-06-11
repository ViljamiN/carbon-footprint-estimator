# Purchase Carbon Footprint Estimator

![Logo](/PCFE.jpg)

## Overview

The Carbon Footprint Estimator is a tool that allows users to estimate the carbon footprint of their purchases by providing an approximate amount of CO2 generated when purchasing specific items.

## Features

- **Add Purchases:** Describe your purchased items, and the app will estimate the associated CO2 footprint.
- **Calculate CO2 Footprint:** Calculate the total estimated CO2 footprint for all added purchases.
- **Logging:** Each purchase, along with its CO2 footprint, is logged for reference.

## Getting Started

### Prerequisites

- Python (version 3.6 or newer)
- [OpenAI GPT-3.5 Turbo API Key](https://platform.openai.com/signup)

### Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo

2. Create a ```.env``` file at the directory with your api key:

   ```bash
   echo OPENAI_API_KEY="your api key here" > .env

3. Run the app with command line interface:

   ```bash
   python impact_estimator.py
