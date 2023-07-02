# ⭐ Follow the steps below for Installation: 

1. Fork and Clone the Repo.
2. Create a copy on your local machine.
3. Open the command prompt.
4. Navigate to the copy created in step 2.
5. Follow the below steps.

###  👉 Create a virtual environment
Write whatever name you prefer (e.g. `conda` or `venv` or `test`)
```console
$ python3 -m venv test
```

### 👉 Activate it
Mac / Linux:
```console
. test/bin/activate
```
Windows:
```console
test\Scripts\activate
```

###  👉 Install PyTorch and dependencies

For Installation of PyTorch see [official website](https://pytorch.org/).

You also need `nltk`:
 ```console
pip install nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```console
$ python
>>> import nltk
>>> nltk.download('punkt')
```

### 👉 Usage
Run
```console
python train.py
```
This will dump `data.pth` file. 

```console
python app.py
```
This will help us connect the chatbot model with the frontend. And then run

```console
python chat.py
```
