<img src="https://github.com/fabiomatricardi/testingStarlingLM/raw/main/starling.png" width=200>

# testingStarlingLM
Test inference GGUF StarlingLM-7B on any computer

Starling-7B, an open large language model (LLM) trained by Reinforcement Learning from AI Feedback (RLAIF). The model harnesses the power of our new GPT-4 labeled ranking dataset, Nectar, and our new reward training and policy tuning pipeline. Starling-7B-alpha scores 8.09 in MT Bench with GPT-4 as a judge, outperforming every model to date on MT-Bench except for OpenAI’s GPT-4 and GPT-4 Turbo. We release the ranking dataset Nectar, the reward model Starling-RM-7B-alpha and the language model Starling-LM-7B-alpha on HuggingFace, and an online demo in LMSYS Chatbot Arena. Stay tuned for our forthcoming code and paper, which will provide more details on the whole process.

### Here the code to run it on your PC
As a good practice create a new folder and a new python virtual environment. I used both a Mac Intel and a Windows PC, with no GPU support, so certainly everyone can run it.
```
mkdir StarlingLM
cd StarlingLM
python -m venv venv     #for windows
python3.10 -m venv venv # for Mac

venv\Scripts\activate     # activate venv on Windows
source venv/bin/activate  #activate the venv on Mac
```
We need only 2 packages to be installed!! So let's grab them
```
pip install llama-cpp-python==0.2.20 #latest version
pip install rich
```
download the python file test.py and with the `venv` activated run
```
python test.py
```


<img src="https://github.com/fabiomatricardi/testingStarlingLM/blob/main/StarlingLM.gif" width=900>
