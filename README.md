# SMS AI Gateway

An Android Automate flow that lets users access AI through SMS.

## How it works

1. Waits for SMS messages.
2. Detects messages starting with `gpt:`.
3. Extracts the prompt.
4. Sends the prompt to an AI API.
5. Receives the response.
6. Splits the response into SMS-sized chunks.
7. Sends the chunks back via SMS.

Built with Automate for Android.
