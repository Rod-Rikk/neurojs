<p align="center"><img src="images/logo-with-demo.png" width="450px"/></p>

neurojs is a JavaScript framework for deep learning in the browser. It mainly focuses on reinforcement learning, but can be used for any neural network based task. It contains neat demos to visualise these capabilities, for instance a 2D self-driving car. 

Feel free to contribute. The development on such projects is more awesome in a community!

### Features
- Implements a full-stack neural-network based machine learning framework
- Extended reinforcement-learning support
	+ Uniform and prioritised replay buffers
	+ Advantage-learning (increasing the action-gap) https://arxiv.org/pdf/1512.04860v1.pdf
	+ Support for **deep-q-networks** and **actor-critic** models (via deep-deterministic-policy-gradients)
- Binary import and export of network configurations (weights etc.)
- High-performance


### Running the web app locally
- First clone the repository : git clone [github link]
- Navigate to the directory(local repository) : cd [name of repository]
- Copy the folder and place it in your htdocs folder of your xampp installation directory
- Open your browser and access the project via localhost:[name of project]


```

Open `http://localhost:8080/examples/` in your browser and select the demo you want to run.

### What's next?
- More examples (pong, pendulum, snake,improved cars, etc.)
- Support for web workers
- LSTM and backpropagation through time
