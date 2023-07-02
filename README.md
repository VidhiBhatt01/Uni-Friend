# Uni-Friend
<br>
<img src="https://github.com/VidhiBhatt01/Uni-Friend/blob/main/Uni%20-%20Friend/Resources/Light%20Theme.png">
<br>
A one step solution to help you ace your exam.

# Inspiration: 💡
- During exam prep, majority of the time of students is wasted in finding the right resource. Also, finding the resources was a huge task on the college telegram channel. Hence, we developed this web app to make the process seamless.

# What it is? 🙄
- A platform where people can find well curated material at one place.
- A platform through which you can access previous year GTU question papers.

# How we built it? 👷‍♂️👷‍♀️
- Tech Stack: <br>
    Fronted = HTML5, CSS3, JS, Bootstrap, Swipper.JS, JQuery, AJAX Google fonts APIs and Netlify for hosting. <br>
    Chatbot = Python, Deep Learning, Jinja templates, Flask, NLTK Libraries, PyTorch
- References: Stack Overflow, W3Schools

# Challenges we ran into: 🏃‍♂️
- Working with AJAX was a little challenging.
- Figuring out the tech stack without increasing the complexity of project was a major task.
- One of the container was causing overflow in the website. Debugging this issue consumed around 2 hours.

# Accomplishments that we are proud of: 🤩
- Building the initial prototype within 36 hours entirely from scratch.
- Successfully achieving the desired targets.

# What's next for Uni-Friend ? 📈
- Smoother UI and complete responsiveness.
- Providing facility to schedule 1:1 session with faculty.
- Light and Dark Theme support.

<hr>

# Installation: 

1. Fork and Clone the Repo.
2. Create a copy on your local machine.
3. Open the command prompt.
4. Navigate to the copy created in step 2.
5. Follow the below steps.

### --> Create a virtual environment
Write whatever name you prefer (e.g. `conda` or `venv` or `test`)
```console
$ python3 -m venv test
```

### --> Activate it
Mac / Linux:
```console
. test/bin/activate
```
Windows:
```console
test\Scripts\activate
```

### --> Install PyTorch and dependencies

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

## --> Usage
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
