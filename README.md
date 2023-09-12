# 🐍 Llama-2-GGML-Medical-Chatbot 🤖
The **Llama-2-7B-Chat-GGML-Medical-Chatbot** is a repository for a medical chatbot that uses the _Llama-2-7B-Chat-GGML_ model and the pdf _The Gale Encyclopedia of Medicine_. The chatbot is still under development, but it has the potential to be a valuable tool for patients, healthcare professionals, and researchers. The chatbot can be used to answer questions about medical topics, provide summaries of medical articles, and generate medical text. However, it is important to note that the chatbot is not a substitute for medical advice from a qualified healthcare professional.

## 📚 Here are some of the features of the Llama-2-7B-Chat-GGML-Medical-Chatbot:

 - It uses the _Llama-2-7B-Chat-GGML_ model, which is a **large language model (LLM)** that has been fine-tuned on a dataset of medical text and code. This means that the model is able to understand and generate text that is relevant to the medical domain.
 - Provided files
Name	 | Quant method	| Bits |	Size	| Max RAM required |	Use case
llama-2-7b-chat.ggmlv3.q2_K.bin	q2_K |	2	| 2.87 GB |	5.37 GB |	New k-quant method. Uses GGML_TYPE_Q4_K for the attention.vw and feed_forward.w2 tensors, GGML_TYPE_Q2_K for the other tensors.
 - It is trained on the pdf **The Gale Encyclopedia of Medicine, Volume 1, 2nd Edition, 637-page PDF**, which is a comprehensive medical reference that provides information on a wide range of medical topics. This means that the chatbot is able to answer questions about a variety of medical topics.
 - This is a sophisticated medical chatbot, developed using Llama-2 7B and Sentence Transformers. Powered by Langchain and Chainlit, this bot operates on a robust CPU machine, boasting a minimum of
    * Operating system: Linux, macOS, or Windows
    * CPU: Intel® Core™ i3
    * RAM: 8 GB
    * Disk space: 7 G
    * GPU: None (CPU only)
      for optimal performance.
 - It is still under development, but it has the potential to be a valuable tool for patients, healthcare professionals, and researchers.
- **Model:** Know more about model [Llama-2-7B-Chat-GGML](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML) 📚
## 🚀 Quickstart
1. Open Git Bash.
2. Change the current working directory to the location where you want the cloned directory.
3. Type `git clone`, and then paste the URL you copied earlier.
```bash
   git clone https://github.com/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot.git
```
Press Enter to create your local clone.
4. Install the pip packages in requirements.txt
 ```bash
   pip install -r requirements.txt
 ```
5. Now run it!
```ternimal
   chainlit run model.py -w
```
## 📖 ChatBot Conversession
![ChatBot Conversession img-1](https://github.com/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot/assets/109382325/9af05b2e-1a83-4a7c-aa8c-ed7c60b02e09)

https://github.com/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot/assets/109382325/6756fb69-40c0-4d49-b392-aa6906dca786

![ChatBot Conversession img-2](https://github.com/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot/assets/109382325/1fede7dd-05e1-49de-bbab-f289cbdb9cd9)

![ChatBot Conversession img-3](https://github.com/ThisIs-Developer/Llama-2-GGML-Medical-Chatbot/assets/109382325/d10d949f-37e5-4ec4-868d-2e62d8ad69dc)
