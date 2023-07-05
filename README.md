# Auto Gnenerate unit test using gpt-3.5-turbo

## Installation:
To install the necessary dependencies, run the following command:

    npm i 

## Usage:

1. In the `ex.js` file, add the relative path to your script file.
2. Add the relative test framework.
3. Create a `.env` file in the root directory of your project and add your OpenAI API key as follows:

          OPENAI_API_KEY=your_api_key_here

3. Run the following commands:
  
         npm run writeTest

         npm run test 


These commands will generate unit tests for your script file using GPT-3.5-Turbo and run them using the specified test framework. The results will be displayed in the console.

Note: Make sure to have your script file and test framework ready before running the commands. If you encounter any issues, please refer to the documentation or seek help from the community.

