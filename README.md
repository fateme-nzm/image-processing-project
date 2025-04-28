markdown
# Noise Type Classification Using ResNet18

This project focuses on classifying different types of noise in images using a deep learning model based on ResNet18.  
The model is trained to distinguish between three types of noise: **Salt & Pepper**, **Gaussian**, and **Periodic** noise.

---

## Project Structure


.
├── data/
│   ├── Labels.csv        # CSV file containing image names and corresponding noise types
│   └── Noisy/             # Folder containing noisy images
├── saved_models/          # Folder where trained models will be saved
├── your_code.py           # Main Python script (the code provided above)
└── README.md              # Project description


---

## Requirements

Make sure you have the following Python libraries installed:

- `torch`
- `torchvision`
- `pandas`
- `numpy`
- `Pillow`
- `scikit-learn`

You can install them using:

bash
pip install torch torchvision pandas numpy pillow scikit-learn


---

## How to Run

1. Clone the repository or download the project files.
2. Ensure your project structure is like the one shown above.
3. Place your noisy images in the `data/Noisy/` folder.
4. Make sure `Labels.csv` is correctly formatted and placed inside the `data/` folder.
5. Run the main script:

bash
python your_code.py


The model will be trained and evaluated, and the trained model will be saved in the `saved_models/` directory.

---

## Notes

- **Dataset:** Make sure the dataset is properly organized and matches the CSV file.
- **Performance Metrics:** After training, the script will output accuracy, precision, recall, and F1-score on the test dataset.
- **Saving the Model:** The trained model is saved automatically as `resnet_noise_classifier.pth`.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

---

## Contact

For any questions or suggestions, feel free to open an issue or contact me via 