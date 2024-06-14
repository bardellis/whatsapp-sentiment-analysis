### Hi there
<!-- COMMENT -->


# WhatsApp Chat Analysis Project

## Overview

This project involves the analysis of WhatsApp chat data to extract meaningful insights and perform sentiment analysis on messages and emojis. The project is divided into multiple Jupyter Notebooks, each focusing on different aspects of the analysis:

1. **ETL (Extract, Transform, Load)**
2. **Exploratory Data Analysis (EDA)**
3. **Message Sentiment Analysis**
4. **Emoji Sentiment Analysis**

## Project Structure

The project consists of the following Jupyter Notebooks:

1. `whatsapp_1-3_ETL_Extract_Transform_Load.ipynb` - This notebook handles the extraction, transformation, and loading of WhatsApp chat data.
2. `whatsapp_41_Msg_Sentiment_Analysis.ipynb` - This notebook focuses on sentiment analysis of the text messages.
3. `whatsapp_42_emoji_Sentiment_Analysis.ipynb` - This notebook performs sentiment analysis on emojis used in the chat data.
5. `whatsapp_5_EDA_Exploratory_Analysis.ipynb` - This notebook performs exploratory data analysis on the chat data to uncover patterns and insights.

## Setup

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook
- Necessary Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly
  - bertopic
  - umap-learn
  - sklearn
  - re
  - datetime

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
 <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>


### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv newenv
   source newenv/Scripts/activate  # On Windows
   # source newenv/bin/activate   # On macOS/Linux
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add the virtual environment to Jupyter as a kernel:**
   ```bash
   python -m ipykernel install --user --name=newenv --display-name "Python (newenv)"
   ```

## Usage

### Running the Notebooks

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open and run the notebooks in the following order:**
   - `whatsapp_1-3_ETL_Extract_Transform_Load.ipynb`
   - `whatsapp_5_EDA_Exploratory_Analysis.ipynb`
   - `whatsapp_41_Msg_Sentiment_Analysis.ipynb`
   - `whatsapp_42_emoji_Sentiment_Analysis.ipynb`

### Notebook Details

#### 1. ETL (Extract, Transform, Load)

This notebook covers:
- Extracting raw WhatsApp chat data.
- Cleaning and transforming the data into a usable format.
- Loading the transformed data for further analysis.

#### 2. Exploratory Data Analysis (EDA)

This notebook covers:
- Descriptive statistics of the chat data.
- Visualization of chat patterns, such as message frequency, word usage, and sender activity.

#### 3. Message Sentiment Analysis

This notebook covers:
- Sentiment analysis of text messages using machine learning techniques.
- Visualization of sentiment trends over time.

#### 4. Emoji Sentiment Analysis

This notebook covers:
- Sentiment analysis of emojis used in the chats.
- Analysis of how emojis correlate with the sentiment of messages.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to all the contributors and the open-source community for their valuable work.
- Special thanks to the authors of the libraries used in this project.

---

This README provides a clear and structured overview of your project, including setup instructions, usage details, and descriptions of each notebook's purpose. Make sure to replace placeholder text like `<repository-url>` and `<repository-directory>` with actual information relevant to your project.
