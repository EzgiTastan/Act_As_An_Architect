The Architectural Response Generator is a project dedicated to creating an automated response as an architect to a given construction site. It leverages neural networks to educate the model on how to design a museum, building, or any other architectural structure for a specific location. The project utilizes programming languages such as Python and a training set comprised of my own unique responses towards the sites given between 2019 and 2023.


# **Features**
**Neural Network Training**: The core functionality of this project involves training a neural network to understand and generate architectural responses based on the given context and site parameters.

**Educational Model**: The model is trained on my responses throughout my own educational journey, ensuring a ***personalized and unique approach to architectural design***.

 **Python Implementation**: The project is implemented primarily in Python, making use of popular libraries for neural network training and natural language processing.

# **Installation**

Clone the repository:
git clone https://github.com/EzgiTastan/act_as_an_architect.git

Navigate to the project directory:
cd act-as-an-architect

Install the required dependencies:
pip install -r requirements.txt


# **Usage**
**Data Preparation**: Ensure that your training data is organized in a structured format. The training set should consist of architectural responses provided by the architect to different construction site scenarios.

**Training the Model**: Run the training script to train the neural network:
python train.py
Adjust hyperparameters and configurations as needed in the script.

**Generating Architectural Responses**: Once the model is trained, use the generation script to get responses for specific construction sites:
python generate_response.py --site_parameters "path/to/site_parameters.json"
Replace "path/to/site_parameters.json" with the actual path to the file containing construction site parameters.

# **Contributing**
Contributions are welcome! If you have ideas for improvements, bug fixes, or additional features, please open an issue or submit a pull request.

# **License**
This project is licensed under the MIT License.

# **Contact**
For questions or discussions, feel free to reach out to me:
kedigunesi@gmail.com

# **More Will be Added**
To optimize performance and enhancing usability, these items will be added over time:

Graphical User Interface (GUI)
Parameter Tuning Interface
Model Evaluation Metrics
Error Handling
Logging and Debugging
Deployment Scripts
CI/CD pipelines
