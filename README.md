# Catch GPT

The project is currently running at: https://catch-gpt.netlify.app/





## Background 
This project extends the (https://github.com/openai/gpt-2-output-dataset/tree/master/detector) made by OpenAI. With additional modifications and optimizations such as

* No token limit. This version splits tokens into batches and then computes the average accuracy across the batches. 
* Custom file upload. Allows the ability to upload files. Currently supports text and pdf files. 
* Zip file support. The app can run through multiple submissions and compute a real probability for each one.
