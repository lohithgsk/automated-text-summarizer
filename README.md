# Automated Text Summarizer
> A tool for condensing extensive amounts of text.
## Bart Large CNN Model
BART, a transformer model, combines a bidirectional encoder (similar to BERT) and an autoregressive decoder (similar to GPT). It's pre-trained by corrupting text using a noise function and learning to reconstruct it. BART excels in tasks like text generation (e.g., summarization, translation) and performs effectively in comprehension tasks (e.g., text classification, question answering). This specific version has been fine-tuned on the CNN Daily Mail dataset, optimizing it for generating summaries from text.

## Demo

![Watch the video](https://github.com/lohithgsk/automated-text-summarizer/blob/main/public/images/demo.gif)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

-  Hugging Face `API_KEY`


## Run Locally

Clone the project
```bash
git clone https://github.com/lohithgsk/automated-text-summarizer.git
 ```

Go to the project directory
```bash 
cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  node index.js
```

## Feedback

If you have any feedback, please reach out to us.
