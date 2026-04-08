# Welcome!

This is the repository for the Deep Learning course developed by the AI Platform at ICN2. 
The course is designed to provide the fundamental concepts and practical skills needed to understand and apply deep 
learning techniques in various domains.

To clone this repo locally, you will have to install `git` on your machine first:

```bash
# For Debian/Ubuntu
sudo apt-get update
sudo apt-get install git

# For macOS
brew install git
```

If you are on Windows, refer to [this](https://git-scm.com/install/windows) link.

Once you have `git` installed, you can clone the repository using the following command:

```bash
git clone https://github.com/icn2-ai/deep-learning-course-spring2026.git
```

Once cloned, you can navigate to the cloned repository and explore the different sessions and materials available. Each session is organized in a Jupyter Notebook format, allowing you to follow along with the code and explanations provided.
Then, you have two different options: 

1. Upload the Jupyter Notebooks to Google Colab and run them there. This is the easiest, least troublesome way to run the notebooks, as you won't have to worry about installing any dependencies. However, you will need a Google account to use Colab.
2. Run the Jupyter Notebooks locally on your machine. This option requires you to set up a Python environment and install the necessary dependencies, but it allows you to work offline and have more control over your environment.

If you choose to run the notebooks locally, you will need to set up a Python environment and install the required dependencies.
To manage our Python dependencies, we use [UV](https://docs.astral.sh/uv/). Refer to the link 
for installation instructions. Once you have UV installed, you can create a virtual environment and install the required dependencies using the following command:

```bash
uv sync
```

Then, to activate the virtual environment, use the following command:

```bash
# For Unix/Linux/MacOS
source .venv/bin/activate

# For Windows
.venv\Scripts\activate
```

To open the Jupyter Notebooks, you can use the following command:

```bash
jupyter notebook
```

---
## Course Structure

The course is structured into four sessions, each covering different aspects of deep learning:
1. **Foundations and Neural Network basics**: This session covers the fundamental concepts of deep learning, including the architecture of neural networks, activation functions, and the backpropagation algorithm.
2. **Data Management and Training Logistics**: This session focuses on data management techniques. It also covers training logistics such as batch size, learning rate, and optimization algorithms, looking as well at the training process and how to monitor it effectively.
3. **Architectures for Diverse Problem Domains**: This session explores various neural network architectures designed for different problem domains, such as convolutional neural networks (CNNs) for image processing, Autoencoders for denoising and feature extraction, and Graph Neural Networks (GNNs) for graph-structured data.
4. **Project presentations**: In this final session, students will present their projects, showcasing the application of deep learning techniques to real-world problems.

### Project

The attendees will be required to complete a project that applies the concepts and techniques learned throughout the course. The project will involve selecting a problem domain, designing and implementing a deep learning model, and evaluating its performance. 
The project will be presented in the final session, where attendees will have the opportunity to share their work and receive feedback from their peers and instructors.