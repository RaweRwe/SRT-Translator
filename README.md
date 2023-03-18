# SRT-Translator

This PHP code uses the Google Cloud Translation API to translate the text in an SRT file from one language to another. It requires a Google Cloud API key, the path to the SRT file, the source language code, and the target language code.

The code reads the SRT file contents, builds a URL with the necessary parameters to send a request to the Google Cloud Translation API, sends the request, and receives a response. The response is then decoded from JSON format into a PHP object, and the translated text is extracted from the response. Finally, the translated text is saved to a new SRT file.

# Note

Note that this code requires the "file_get_contents" and "file_put_contents" functions to be enabled in your PHP configuration.
