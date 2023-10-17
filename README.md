# StyleGAN_Prompt_Animation

Developed by Pirate-Emperor, StyleGAN_Prompt_Animation is a Python-based machine learning project, implemented in a Jupyter Notebook, that focuses on generating prompt-driven animations using the StyleGAN architecture.

## Features

- **StyleGAN Animation**: Generates animations by interpolating between latent vectors corresponding to different text prompts.
- **Latent Space Exploration**: Explore the latent space of a pre-trained StyleGAN model.
- **Text-to-Image**: Transforms text prompts into images using a pre-trained StyleGAN model.
- **Customizable**: You can customize the text prompts, animation duration, and number of frames.
- **Prompt-Driven Generation**: Takes textual prompts as input and generates animations that align with the descriptions in the prompts.
- **StyleGAN Integration**: Utilizes the StyleGAN architecture to generate high-quality and coherent images based on the given prompts.
- **Animation Creation**: Combines the generated images into a smooth animation, showcasing the transition between different prompts.
- **Data Preprocessing**: Cleans and preprocesses the text prompts for effective input processing.
- **Fine-Tuning**: Optionally fine-tunes the StyleGAN model on a custom dataset to improve prompt alignment and image generation.
- **Visualization**: Generates plots and charts to display the generated images, animations, and model performance.
  
## Prerequisites

To run the project, you'll need:

- Python 3.x
- Required Python libraries (e.g., torch, transformers, PIL, matplotlib)
- Jupyter Notebook

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/Pirate-Emperor/StyleGAN_Prompt_Animation.git
cd StyleGAN_Prompt_Animation
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Navigate to the `StyleGAN_Prompt_Animation.ipynb` file and open it.

Execute the cells in the notebook to preprocess data, generate images based on prompts, create animations, and visualize results.
You will be prompted to input the text prompts for the start and end of the animation, the duration of the animation, and the number of frames. The script will generate a sequence of images that interpolate between the latent vectors corresponding to the text prompts.

## Data Source

The project uses the StyleGAN pre-trained model, which is trained on a diverse dataset of images. 


## Development

To enhance the project, you can modify the Jupyter Notebook (`StyleGAN_Prompt_Animation.ipynb`). Areas for improvement include:

- Incorporating more advanced text-to-image models and techniques for better prompt alignment.
- Experimenting with different animation techniques to create more engaging and visually appealing animations.
- Developing a user interface for users to input prompts and view generated animations.
- Expanding the application to include features such as user-defined animation durations, frame rates, and transition styles.
- Enhancing the quality of the generated images
- Reducing the computation time
- Implementing more sophisticated text-to-image models

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.



