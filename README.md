# StoryaheAI

StoryaheAI is a web application built with Django and Python that uses the OpenAI API to generate short stories based on user input. The application takes user input in the form of a prompt and uses the GPT-3.5 model from OpenAI to generate a short story based on that prompt.

## Installation

To use StoryaheAI, you will need to have Python and Django installed on your computer. You will also need to sign up for an OpenAI API key.

Once you have Python and Django installed, you can clone the repository and install the necessary packages by running:

```bash
git clone https://github.com/<username>/storyaheai.git
cd storyaheai
pip install -r requirements.txt
```

You will also need to create a `.env` file in the root directory of the project and add your OpenAI API key to it, like this:

```bash 
OPENAI_API_KEY=<your_api_key>
```

## Usage

To start the application, navigate to the root directory of the project and run the following command:


This will start the Django development server, and you can access the application by navigating to http://localhost:8000 in your web browser.

To generate a short story, simply enter a prompt in the input field and click the "Generate" button. The application will then use the OpenAI API to generate a short story based on your prompt and display it on the page.

## Contributing

If you would like to contribute to StoryaheAI, you can fork the repository and submit a pull request with your changes. Please make sure to write clear and concise commit messages and follow the project's coding standards.

## License

StoryaheAI is licensed under the MIT License.



