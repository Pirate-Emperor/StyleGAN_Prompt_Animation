# StyleGAN Prompt Animation Project

This project demonstrates the creation of animations using StyleGAN and text prompts. The project generates a sequence of images by interpolating between latent vectors corresponding to different text prompts.

## Features

- **StyleGAN Animation**: Generates animations by interpolating between latent vectors corresponding to different text prompts.
- **Latent Space Exploration**: Explore the latent space of a pre-trained StyleGAN model.
- **Text-to-Image**: Transforms text prompts into images using a pre-trained StyleGAN model.
- **Customizable**: You can customize the text prompts, animation duration, and number of frames.

## Prerequisites

To run the project, you will need:

- Python 3.x
- Required Python libraries (numpy, torch, torchvision, etc.)
- A pre-trained StyleGAN model (e.g., StyleGAN2 or StyleGAN3)

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

Download the pre-trained StyleGAN model and place it in the project directory.

## Usage

Run the main Python script:

```bash
python main.py
```

You will be prompted to input the text prompts for the start and end of the animation, the duration of the animation, and the number of frames. The script will generate a sequence of images that interpolate between the latent vectors corresponding to the text prompts.

## Development

To add more features or improve the existing ones, you can modify the Python scripts in the `src` directory. Some potential areas for improvement include:

- Enhancing the quality of the generated images
- Reducing the computation time
- Implementing more sophisticated text-to-image models

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
