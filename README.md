# PhoneChooserAI

Welcome to PhoneChooserAI! This application helps you find the best smartphone based on your preferences. You can select various specifications such as RAM, Storage, Camera, Processor, Display Size, Price Range, and provide additional details in a text area to get the best phone suggestions.

## Features

- **Select RAM options**: Choose from 2 GB to 16 GB.
- **Select Storage options**: Choose from 16 GB to 1 TB.
- **Select Camera options**: Choose from 8 MP to 108 MP.
- **Select Processor options**: Choose from Quad-Core to A14 Bionic.
- **Select Display Size options**: Choose from 5.0" to 6.9".
- **Select Price Range**: Adjust the slider to set your preferred price range.
- **Write Prompt**: Optionally, provide additional details or preferences in a text area.
- **Get Recommendations**: The app filters and displays smartphones that match your criteria.

## Installation

To run this application locally, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/AyushBhavsar/PhoneChooserAI.git
   cd PhoneChooserAI
   ```

2. **Install the required dependencies**:

   ```sh
   pip install streamlit uagents groq nest_asyncio
   ```

3. **Set your Groq API key**:

   ```sh
   export groq_api_key='YOUR_GROQ_API_KEY'
   ```

4. **Run the application**:
   ```sh
   streamlit run main.py
   ```

## Usage

1. **Start the application**: Follow the installation steps to run the application locally.
2. **Select your preferences**: Use the provided options to select your desired phone specifications.
3. **View recommendations**: The app will display a list of smartphones that match your selected criteria.

## Code Explanation

### main.py

The main entry point of the application which handles the user interface and interactions.

### utils.py

Contains utility functions such as `generate_prompt` to create the query prompt for phone specifications.

### agent.py

Handles the interaction with the Groq API, encapsulating the logic for making requests and processing responses.

## Contribution

You are free to contribute.


## Snaps

![Screenshot 1 of the application](assets/ss1.png)
![Screenshot 2 of the application](assets/ss2.png)

